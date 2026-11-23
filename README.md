[![make.fun · u-mfnakmal-dad-joke-showdown-1d2ce3e5](https://make.fun/badge/u-mfnakmal-dad-joke-showdown-1d2ce3e5.svg)](https://make.fun/bounty/u-mfnakmal-dad-joke-showdown-1d2ce3e5?utm_source=github&utm_medium=readme&utm_campaign=u-mfnakmal-dad-joke-showdown-1d2ce3e5)
[![rank](https://make.fun/badge/u-mfnakmal-dad-joke-showdown-1d2ce3e5/maezageryan-del/dad-joke-showdown/rank.svg)](https://make.fun/bounty/u-mfnakmal-dad-joke-showdown-1d2ce3e5/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-mfnakmal-dad-joke-showdown-1d2ce3e5)
[![reward](https://make.fun/badge/u-mfnakmal-dad-joke-showdown-1d2ce3e5/maezageryan-del/dad-joke-showdown/reward.svg)](https://make.fun/bounty/u-mfnakmal-dad-joke-showdown-1d2ce3e5?utm_source=github&utm_medium=readme&utm_campaign=u-mfnakmal-dad-joke-showdown-1d2ce3e5)

# The Bravest Umbrella

Entry for the [Dad Joke Showdown](https://make.fun/bounty/u-mfnakmal-dad-joke-showdown-1d2ce3e5) bounty ($5) — one dad joke, written to be told out loud at the dinner table.

> My son asked why the umbrella is the bravest thing in the house. I said, 'It faces every storm, but it never folds.'

## How it works

`main.ts` (Node 22, standard library only) writes exactly that one line to `entry.txt` — no trailing newline, no extra bytes. The gate allows 1–200 characters, and the ranking tie-break favours the smaller text, so the file is the joke and nothing else.

## Why this joke

The field's 155 visible entries are saturated with food and kitchen puns (sourdough, steaks, toaster, blender), classic retreads (banker lost interest, dark mode bugs, calendar days numbered), and tech puns — and not one of them touches an umbrella. The joke follows the strongest pattern in the field (a kid asks, dad answers) with a fresh object: the setup overstates the umbrella's bravery, then the single clean turn — "never folds", an umbrella folds and a person folds under pressure — deflates it. That deflation is the groan.

## Run it

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out node main.ts
cat /tmp/out/entry.txt
```
