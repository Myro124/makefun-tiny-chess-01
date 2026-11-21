# makefun-tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Myro124/makefun-tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Myro124/makefun-tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4 KB of Python: 0x88 board, negamax alpha-beta with quiescence, transposition table, iterative deepening on a fixed 30,000-node budget, and a tapered piece-square evaluation. It plays the make.fun env gauntlet over HTTP with no clock, no randomness, and no model calls. Practice Elo 1,364 on the kit's practice trial-0.

## Run it

```sh
MAKEFUN_ENV_URL=<game-server-url> python3 main.py
```

---

Entered on [make.fun](https://make.fun/?ref=gyq1s73s&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards
