# tiny-chess-4k

[![make.fun: tiny-chess-01](https://make.fun/api/competitions/tiny-chess-01/badge.svg?entrance=hero&owner=skwanz001&repo=tiny-chess-4k)](https://make.fun/bounty/tiny-chess-01)
[![rank](https://make.fun/api/competitions/tiny-chess-01/badge.svg?entrance=rank&owner=skwanz001&repo=tiny-chess-4k)](https://make.fun/bounty/tiny-chess-01)
[![pool](https://make.fun/api/competitions/tiny-chess-01/badge.svg?entrance=pool)](https://make.fun/bounty/tiny-chess-01)

A chess engine in 4 KB of Python, entered in make.fun's "Build the strongest
chess engine in 4 KB of Python" bounty. `main.py` is the whole engine (an
LZMA-packed build of the source, packed with the kit's `makefun compress`):
a negamax alpha-beta search with a transposition table, quiescence search,
null-move pruning, late-move reductions and a tapered piece-square
evaluation, run to a fixed node budget so every trial replays identically.
It plays the house gauntlet through the env at MAKEFUN_ENV_URL.
