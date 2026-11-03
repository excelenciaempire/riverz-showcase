# Riverz AI engineering

## Shared editing rules

The web editor, commands and desktop editor use a shared planning layer for media edits. A separated video/audio pair has explicit identities, timing and sound settings. Separation is one undoable operation; restore preserves unrelated visual edits and refuses ambiguous pairs.

## Project state and recovery

Stable command IDs let an interrupted operation recover its result without applying an edit twice. Revision comparisons prevent stale commands from replacing newer work. Generation, media availability and placement in the timeline have separate states.

## Media validation

The private implementation includes regression tests for editing and persistence, alongside native FFmpeg/ffprobe checks where rendered output matters. A timeline mute flag must produce silence in the exported media. Desktop runtime checks cover a different environment from web tests.

These notes summarize the implementation and its validation approach; they are not a current whole-product CI report.

[Component cases](CASES.md) · [Product overview](README.md)
