# makefun-tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/haidirnur/makefun-tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/haidirnur/makefun-tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A deterministic 0x88 mailbox chess engine in 3,982 bytes of Python: alpha-beta search with iterative deepening (depth 1–9) on a fixed 200,000-node budget, a transposition table, killer/history move ordering, retuned piece-square evaluation with a tapered king term, in-search repetition scoring, late-move reductions (LMR), and full legal-move protocol (castling, en passant, promotion). It talks to the make.fun env over HTTP and never reads a clock, so every replay plays the same moves.

## Run it

```sh
MAKEFUN_ENV_URL=http://localhost:PORT python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=16t6wrwd&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
