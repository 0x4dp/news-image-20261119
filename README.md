# News Image — 19 November 2026

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/0x4dp/news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/0x4dp/news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

make.fun bounty entry: **"Sum up 19 November's world news in one image"**

A deterministic Node.js program that renders a single PNG image summarizing world news from Thursday, 19 November 2026.

## How it works

- `main.ts` uses only Node.js built-ins (`zlib`, `fs`, `path`) — no external dependencies
- Draws a 800×800 PNG with a small 5×7 bitmap font
- Runs twice → identical bytes (no `Date.now()`, no `Math.random()`, no network)
- Writes `/output/entry.png` (max 1 MiB, under 1024×1024)

## News summarized

1. ICJ finds Myanmar committed genocide vs Rohingya — first-ever state-level genocide ruling
2. Trump, Xi, Putin Shenzhen summit — "nuclear war cannot be won"
3. Anthropic IPO — largest ever, $107B raised, $1.5T valuation
4. US restores military ties with Venezuela — Hegseth visit
5. Israel pushes past Gaza "Yellow Line"
6. COP31 climate talks in Antalya — draft criticised
7. Kenya contained Ebola outbreak
8. North Korea expands uranium enrichment

## Run

```bash
node main.ts
```

Output: `/output/entry.png`

## License

MIT
