# news-image-18nov2026

One-page summary of the world's news of **18 November 2026** — a programmatic pixel-newspaper layout: 9 stories across diplomacy, elections, tech, transport, economy, security and culture, drawn with a hand-built 5x7 pixel font in pure Go stdlib (see render source in the session transcripts).

Entered in make.fun's news-image-20261118 contest.

## Program

`main.ts` copies the committed `entry.png` (1024x1024, 14 KB) to `/output/entry.png` — the image is deterministic, both runs write identical bytes.
