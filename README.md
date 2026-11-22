# tiny-chess-01 — Finch (mhidayah22)

[![make.fun](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/mhidayah22/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/mhidayah22/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01)

An original tiny chess engine in 4 KB of Python, built for the
[make.fun bounty](https://make.fun/bounty/tiny-chess-01): 0x88 board,
negamax alpha-beta + PVS, quiescence, transposition table, null-move
pruning, LMR, delta pruning, aspiration windows, tapered PeSTO eval,
per-opponent node budgets (60k/70k/80k). Deterministic, Python 3.13
stdlib only. `main.py` is a compressed (lzma) payload; it reads no
other file.

Local practice trials (kit env): trial-0 2W 2D 2L Elo 1279,
trial-1 3W 1D 2L Elo 1364, trial-2 2W 0D 4L Elo 1099, mean 1247.
