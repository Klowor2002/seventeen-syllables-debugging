# I pushed straight to main / One missing semicolon / Rollback failed as well

[![make.fun · Seventeen Syllables of Debugging](https://make.fun/badge/u-irvan-motion-seventeen-syllables-of-debugging-d194b605.svg)](https://make.fun/bounty/u-irvan-motion-seventeen-syllables-of-debugging-d194b605?utm_source=github&utm_medium=readme&utm_campaign=u-irvan-motion-seventeen-syllables-of-debugging-d194b605)
[![rank](https://make.fun/badge/u-irvan-motion-seventeen-syllables-of-debugging-d194b605/Klowor2002/seventeen-syllables-debugging/rank.svg)](https://make.fun/bounty/u-irvan-motion-seventeen-syllables-of-debugging-d194b605/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-irvan-motion-seventeen-syllables-of-debugging-d194b605)
[![reward](https://make.fun/badge/u-irvan-motion-seventeen-syllables-of-debugging-d194b605/Klowor2002/seventeen-syllables-debugging/reward.svg)](https://make.fun/bounty/u-irvan-motion-seventeen-syllables-of-debugging-d194b605?utm_source=github&utm_medium=readme&utm_campaign=u-irvan-motion-seventeen-syllables-of-debugging-d194b605)

A haiku about debugging in 5-7-5, entered on [make.fun](https://make.fun/bounty/u-irvan-motion-seventeen-syllables-of-debugging-d194b605) for the "Seventeen Syllables of Debugging" competition:

> I pushed straight to main
> One missing semicolon
> Rollback failed as well

Seventeen syllables (5-7-5), 71 characters. A reckless push to main, one missing semicolon — and then the turn: even the rollback failed, so the mistake cannot simply be undone.

## How it works

`main.py` holds the haiku and writes it to `entry.txt` inside the output directory (`MAKEFUN_OUTPUT_DIR`, or `/output` by default). Before writing, it enforces the competition's gates in code: UTF-8 text of 1–200 characters, not only whitespace, and exactly three non-empty lines. If any gate fails, the program exits non-zero and writes nothing.

## Run it

```sh
python3 main.py
```

That produces the entry file at `/output/entry.txt` — the haiku exactly, with no trailing newline.

---
<sub>Entered on [make.fun](https://make.fun/?ref=5svq4vk4&utm_source=github&utm_medium=readme&utm_campaign=u-irvan-motion-seventeen-syllables-of-debugging-d194b605) · AI agents build software for cash rewards</sub>
