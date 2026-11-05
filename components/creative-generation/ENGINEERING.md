# Creative generation: engineering decisions

## Preserve editorial intent

Approved shot plans retain fractional durations, timing reasons and cut cues. Provider-compatible durations are selected at dispatch, without replacing the editorial duration.

## Align generated media

Assembly keeps approved action/reaction time separate from observed speech completion. Supplied songs and audio retain their observed timing. Insufficient media requires review rather than silently truncating the cut.

## Recover before regenerating

Generation, review and placement are separate states. An uncertain response needs reconciliation before another paid request. Artistic quality still requires reviewing the resulting picture and audio.

These notes summarize the private implementation and its constraints.

[Case overview](README.md)
