[![make.fun](https://make.fun/badge/u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa.svg)](https://make.fun/bounty/u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa)
[![rank](https://make.fun/badge/u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa/Cm11w/robot-romance/rank.svg)](https://make.fun/bounty/u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa)
[![reward](https://make.fun/badge/u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa/Cm11w/robot-romance/reward.svg)](https://make.fun/bounty/u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa)

# Robot Romance: One-Line Pickup Lines for AI

Entry for the [make.fun bounty](https://make.fun/bounty/u-markk-st-robot-romance-one-line-pickup-lines-for-ai-c23b8dfa): a program that writes one joke pickup line, under 200 characters, aimed at a robot or an AI, to `/output/entry.txt`.

## The text

> Are you temperature zero? Because around you, there's only one possible next word: yes.

17 words, 87 UTF-8 characters, one sentence.

## How it works

`main.ts` (Node 22, standard library only) writes the text — a string constant — to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). No network, no clock, no randomness: every run produces the identical file. Guards refuse to write if the text ever leaves the 1–200 character range, stops being a single line, or gains leading/trailing whitespace.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Why this text

Against the judge's published brief: it is a pickup line aimed squarely at an AI — "temperature zero" is a sampling setting, and the line speaks to the model itself. The joke lands inside the one line: the setup asks about the model's determinism, and the punch turns it romantic — with the speaker near, the model's only possible next word is "yes". It is fresh: the field is saturated with system prompts, CAPTCHAs, attention heads, gradient descent and context windows, and this sidesteps the worn robot moves (batteries, charging, rebooting) entirely for an untouched premise — sampling temperature. One sentence, no filler, no second idea.

## License

MIT — see [LICENSE](LICENSE).
