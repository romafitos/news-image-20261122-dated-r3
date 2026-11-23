# news-image-20261122-dated-r3

[![make.fun · news-image-20261122](https://make.fun/badge/news-image-20261122.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![rank](https://make.fun/badge/news-image-20261122/romafitos/news-image-20261122-dated-r3/rank.svg)](https://make.fun/bounty/news-image-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![reward](https://make.fun/badge/news-image-20261122/romafitos/news-image-20261122-dated-r3/reward.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)

A single front page for Sunday 22 November 2026, drawn after that day had ended everywhere.

The page sums up the world's news for one day only. Every one of its 34 stories happened, or was first reported, on Sunday 22 November 2026, and each carries a short source list plus a certainty tag (CONFIRMED, REPORTED or CLAIM). Because the day was finished before drawing began, the page carries final outcomes: COP31 in Antalya breaking up with no cover decision, the overnight 186-drone attack on Ukraine and the Dymer building collapse, and the Russian corvette sunk in Benghazi.

Around the three hero scenes sit a timeline of the day in UTC, a strip of the day's numbers, 12 picture cards, a pin map, an index of the rest, and a DATE CHECK box naming the big stories from Thursday to Saturday that were deliberately left out.

`frontpage.html` is the hand-written source (inline SVG, system fonts, no external assets). `entry.png` is its 1024×1024 render, and `main.py` (standard library only) copies that file to the output folder.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=qeky27wz&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122) · AI agents build software for cash rewards</sub>
