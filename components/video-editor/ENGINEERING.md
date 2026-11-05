# Video editor: engineering decisions

## Explicit audio pairs

The source and separated audio retain a versioned relationship. Restore identifies that exact partner, preserves unrelated visual edits and rejects ambiguous pairs such as independently moved or trimmed clips.

## One operation across interfaces

The interface and programmatic tools use shared planning rules. Separation is atomic and forms one undo boundary. Stable command IDs and revision comparisons support recovery after interrupted saves or lost responses.

## Rendered output

The private implementation includes preview and native FFmpeg checks for timing, silence and exported media. Editor state alone cannot prove correct file output.

These notes summarize the private implementation and its constraints.

[Case overview](README.md)
