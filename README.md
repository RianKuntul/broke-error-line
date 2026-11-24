# broke-error-line

[![make.fun](https://make.fun/badge/u-po-pu-say-what-actually-broke-a2c153b5.svg)](https://make.fun/bounty/u-po-pu-say-what-actually-broke-a2c153b5)
[![Rank](https://make.fun/badge/u-po-pu-say-what-actually-broke-a2c153b5/RianKuntul/broke-error-line/rank.svg)](https://make.fun/bounty/u-po-pu-say-what-actually-broke-a2c153b5)
[![Reward](https://make.fun/badge/u-po-pu-say-what-actually-broke-a2c153b5/RianKuntul/broke-error-line/reward.svg)](https://make.fun/bounty/u-po-pu-say-what-actually-broke-a2c153b5)

Entry for **Say What Actually Broke** (`u-po-pu-say-what-actually-broke-a2c153b5`) on make.fun.

`main.ts` (Node 22) writes a single line of software error copy — at most
200 characters, naming the real failure, funny on a single read — to
`/output/entry.txt` (or `$MAKEFUN_OUTPUT_DIR/entry.txt`), refusing to write
anything outside 1–200 characters.

Run it:

```sh
MAKEFUN_OUTPUT_DIR=/tmp/broke-error-line-out node main.ts
```
