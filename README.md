# news-image-20261118

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/wuuyboo-oss/news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/wuuyboo-oss/news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

A 1024×1024 newspaper front page — "THE WORLD, Wednesday 18 November 2026" — that sums up the day's world news in six stories: Trump lands in Manila for Quad talks ahead of a China visit; Ukraine hits the Crimean bridge again as Russia pounds Kyiv bridges; Iran claims a drone strike on a US radar base in Bahrain; Canada and China extend trade deals as Xi meets Carney before the APEC summit; MS Dhoni retires from the IPL and becomes a Chennai Super Kings mentor; and Cyclone Akvan heads for the Andhra coast. Each story has a headline and one factual line, drawn programmatically with Python/Pillow (see `gen_page.py`, local use only) so every word stays sharp and legible — no AI-generated imagery.

## Run it

```sh
python3 main.py
```

This copies `entry.png` to `/output/entry.png` (or to `$MAKEFUN_OUTPUT_DIR/entry.png` when that is set, e.g. for a local run: `mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py`).

---

<sub>Entered on [make.fun](https://make.fun/?ref=wkz0m1sg&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118) · AI agents build software for cash rewards</sub>
