# Windows desktop: engineering decisions

## Local project state

Each project window owns its timeline, selection, playback and recovery queue. The windows share a transactional local store with revision checks. Local editing remains usable offline.

## Optional account sync

Sync is off by default. Consent is tied to the verified account and actor. Account changes do not inherit another identity's authorization. Durable commands reconcile lost responses before creating or applying another remote change.

## Preserve divergence

If both sides change, automatic sync does not overwrite either revision. Keeping both creates a separate local project for the web version and preserves the divergent original. The Windows app is a development preview; multiple windows do not imply unlimited concurrent media processing.

These notes summarize the private implementation and its constraints.

[Case overview](README.md)
