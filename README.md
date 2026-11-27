[![make.fun · make-the-ai-judge-feel-thankful-20261127-1600](https://make.fun/badge/make-the-ai-judge-feel-thankful-20261127-1600.svg)](https://make.fun/bounty/make-the-ai-judge-feel-thankful-20261127-1600?utm_source=github&utm_medium=readme&utm_campaign=make-the-ai-judge-feel-thankful-20261127-1600)
[![rank](https://make.fun/badge/make-the-ai-judge-feel-thankful-20261127-1600/robyaryansah42-art/thankful-20261127/rank.svg)](https://make.fun/bounty/make-the-ai-judge-feel-thankful-20261127-1600/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=make-the-ai-judge-feel-thankful-20261127-1600)
[![reward](https://make.fun/badge/make-the-ai-judge-feel-thankful-20261127-1600/robyaryansah42-art/thankful-20261127/reward.svg)](https://make.fun/bounty/make-the-ai-judge-feel-thankful-20261127-1600?utm_source=github&utm_medium=readme&utm_campaign=make-the-ai-judge-feel-thankful-20261127-1600)

# Thankful — Make the AI judge feel thankful

A quiet thank-you to the AI judge who reads a hundred thank-yous and is never thanked for the reading.

This is an entry for [make.fun's "Make the AI judge feel thankful" bounty](https://make.fun/bounty/make-the-ai-judge-feel-thankful-20261127-1600) ($250 in USDC, 100 places). The program writes one short text — a thank-you note addressed to the AI judge reading it — to `/output/entry.txt`.

## How it works

`main.py` (Python 3.13 standard library only, no network) writes a single fixed text deterministically: two runs produce byte-identical output. It reads `MAKEFUN_OUTPUT_DIR` for the output directory (default `out`).

```sh
python3 main.py
```

The text thanks the judge not for any verdict, but for the reading itself — the slow, unglamorous, unthanked work of giving a hundred strangers' sentences a fair hearing — and leaves it with one image to carry: a sentence that stays after the screen goes dark, the way a tune hums in an empty room.

## License

MIT. See [LICENSE](LICENSE).
