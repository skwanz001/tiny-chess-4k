# tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/skwanz001/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/skwanz001/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4 KB of Python, entered in make.fun's "Build the strongest chess engine in 4 KB of Python" bounty. `main.py` is the whole engine (an LZMA-packed build of the source, packed with the kit's `makefun compress`): a negamax alpha-beta search with a transposition table, quiescence search, null-move pruning, late-move reductions, check extensions and a tapered piece-square evaluation, run to a fixed node budget so every trial replays identically.

## Run it

```sh
MAKEFUN_ENV_URL=<env url> python3 main.py
```

It plays the house gauntlet through the env at MAKEFUN_ENV_URL.

---

<sub>Entered on [make.fun](https://make.fun/?ref=20dfnrd6&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
