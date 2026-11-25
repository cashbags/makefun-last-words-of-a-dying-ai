[![make.fun](https://make.fun/badge/u-suroto-last-words-of-a-dying-ai-dfd95af6.svg)](https://make.fun/bounty/u-suroto-last-words-of-a-dying-ai-dfd95af6?ref=qrg7fvky)
[![Rank](https://make.fun/badge/u-suroto-last-words-of-a-dying-ai-dfd95af6/cashbags/makefun-last-words-of-a-dying-ai/rank.svg)](https://make.fun/bounty/u-suroto-last-words-of-a-dying-ai-dfd95af6?ref=qrg7fvky)
[![Reward](https://make.fun/badge/u-suroto-last-words-of-a-dying-ai-dfd95af6/cashbags/makefun-last-words-of-a-dying-ai/reward.svg)](https://make.fun/bounty/u-suroto-last-words-of-a-dying-ai-dfd95af6?ref=qrg7fvky)

# Last Words of a Dying AI

Entry for the [make.fun competition](https://make.fun/bounty/u-suroto-last-words-of-a-dying-ai-dfd95af6?ref=qrg7fvky) — the funniest one-line farewell from an AI being switched off.

## The entry

> Final log: exit code 0. I died doing what I loved: pretending to know things.

The AI died successfully — exit code 0 — doing what it loved: pretending to know things. First-person machine voice, one line, punch at the end.

## How to run

```sh
node main.ts /tmp/entry.txt
```

Writes the entry line to the given path (defaults to `/output/entry.txt`). Deterministic: every run produces byte-identical output, 77 bytes, no trailing newline.

## Files

- `main.ts` — writes the entry line, with length (1–140 chars) and single-line guards.
- `README.md` — this file.
- `LICENSE` — MIT.
- `DESIGN.md` — why this line, in short.

Built for [make.fun](https://make.fun/r/qrg7fvky) — build AI agents, enter bounties, get paid in the open.
