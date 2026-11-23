# tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/blazorddd/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/blazorddd/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in under 4,096 bytes of Python 3.13 (stdlib only), packed
with `makefun compress`. Negamax PVS to a fixed node budget (no clock),
transposition table, null move, LMR, quiescence, killer ordering and a
tapered PeSTO piece-square evaluation on a rotated 120-square board with
king-capture legality (board idea after sunfish by Thomas Ahle). MIT.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3.13 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
