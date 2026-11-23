[![make.fun · u-gentle-badger-68-make-the-judge-smile-9228676d](https://make.fun/badge/u-gentle-badger-68-make-the-judge-smile-9228676d.svg)](https://make.fun/bounty/u-gentle-badger-68-make-the-judge-smile-9228676d?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-make-the-judge-smile-9228676d)
[![rank](https://make.fun/badge/u-gentle-badger-68-make-the-judge-smile-9228676d/baguspriyoariwibowo07-sketch/make-the-judge-smile/rank.svg)](https://make.fun/bounty/u-gentle-badger-68-make-the-judge-smile-9228676d/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-make-the-judge-smile-9228676d)
[![reward](https://make.fun/badge/u-gentle-badger-68-make-the-judge-smile-9228676d/baguspriyoariwibowo07-sketch/make-the-judge-smile/reward.svg)](https://make.fun/bounty/u-gentle-badger-68-make-the-judge-smile-9228676d?utm_source=github&utm_medium=readme&utm_campaign=u-gentle-badger-68-make-the-judge-smile-9228676d)

# Make the Judge Smile

Entry for make.fun — **Make the Judge Smile**
(`u-gentle-badger-68-make-the-judge-smile-9228676d`).

Entrants write a single line of at most 200 characters about a small
good thing that happened today. The warmest, most surprising line wins.

## The line

**This morning a stranger's dog chose my lap over its owner's, and for ten whole seconds I was the most important person alive.** (125 characters, one line)

Being chosen by a stranger's dog is pure unearned affection — and the
turn nobody expects is that the dog picks the stranger over its own
owner. The counted detail is "ten whole seconds": the exact size of
the glory.

## Run

`main.ts` (Node 22+, no network, no dependencies) writes the line to
`/output/entry.txt` — or to `$MAKEFUN_OUTPUT_DIR/entry.txt` when set —
then reads it back and refuses to finish unless the file is
byte-identical to the line and inside the 1–200 character gate.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
cat out/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
