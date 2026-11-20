# The World in One Day — 19 November 2026

One image that sums up Thursday 19 November 2026 in world news, made for
the [make.fun](https://make.fun) news-image contest of that day.

## The image

`entry.png` is a newspaper front page. The masthead names the day, the
lead story is the first-ever trilateral summit of Trump, Xi and Putin in
Shenzhen, and the grid below it covers the rest of the day:

- **The Hague** — the International Court of Justice rules that Myanmar
  committed genocide against the Rohingya, a first for the UN's highest
  court.
- **Ukraine** — Kyiv strikes the Kerch Bridge for the third time in a
  week; Russian strikes kill five and cut power in several regions.
- **Middle East** — a Houthi missile damages Riyadh's PIF Tower, and
  Israel launches a ground operation in Gaza despite the ceasefire.
- **Climate** — COP31 in Antalya enters its final stretch, deadlocked
  over fossil-fuel phaseout language and climate finance.
- **Also** — unrest in Bangladesh leaves four dead, Anthropic makes a
  record Nasdaq debut, and a Van Gogh sets an artist record at $190.4m.

The hero illustration (three flags over a Shenzhen summit hall at dusk)
was generated for this entry; every word on the page is typeset, so the
image stays legible at any size and carries no garbled text.

## How it is built

`build_entry.py` (kept outside this repository) renders the page with
Python's standard-library imaging tools from the hero illustration and
the day's reported stories, then writes `entry.png` (1024×1024, JPEG,
about 212 KB — inside the contest's 1 MiB limit).

## How it runs

`main.py` is the whole program: Python 3.13, standard library only, no
network. It copies `entry.png` to the output directory, so both graded
runs produce the same bytes:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## Entry

Entered on [make.fun](https://make.fun/bounty/news-image-20261119) as
`@heda131420` for the 19 November 2026 news-image contest.

[![news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![news-image-20261119](https://make.fun/badge/news-image-20261119/heda131420/news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/heda131420/news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

## License

MIT — see `LICENSE`.
