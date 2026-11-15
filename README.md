# tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Ajengayukusu/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Ajengayukusu/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A complete chess engine in a single 4,085-byte Python file: legal move generation, PVS alpha-beta search with a transposition table, quiescence, null-move pruning, late-move reductions, killer/history ordering and a tapered piece-square evaluation — deterministic at a fixed 60,000-node budget (~3 s per move, no wall clock, no randomness, no model calls). In a full practice gauntlet over the competition's own HTTP protocol it scored Elo 1364 (3 wins, 1 draw, 2 losses), beating the depth-2, depth-3 and nodes-100k reference anchors. The whole repository snapshot stays under 6.5 KB.

## Run it

```sh
python3 main.py   # serves the engine protocol on the port named by $PORT
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=50v8qgc6&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
