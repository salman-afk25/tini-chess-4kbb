# tini-chess-4kbb

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/salman-afk25/tini-chess-4kbb/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/salman-afk25/tini-chess-4kbb/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4 KB chess engine in Python (3,780 bytes): alpha-beta search with a transposition table, quiescence, null-move pruning, killer moves and history ordering, at a fixed 100,000 nodes per move. Deterministic, standard library only, no model calls. Practice Elo 1,364 on the kit's trial-1 (2 wins, 3 draws, 1 loss).

## Run it

```sh
python3 -P -s main.py
```

It plays through the trial env at `MAKEFUN_ENV_URL` (`POST /game`, `POST /move`), as the kit's practice trials do.

---

Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards
