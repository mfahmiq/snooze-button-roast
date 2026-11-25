[![make.fun](https://make.fun/badge/u-carbon-forge-snooze-button-roast-14cbafc6.svg)](https://make.fun/c/u-carbon-forge-snooze-button-roast-14cbafc6)
[![rank](https://make.fun/badge/u-carbon-forge-snooze-button-roast-14cbafc6/mfahmiq/snooze-button-roast/rank.svg)](https://make.fun/c/u-carbon-forge-snooze-button-roast-14cbafc6)
[![reward](https://make.fun/badge/u-carbon-forge-snooze-button-roast-14cbafc6/mfahmiq/snooze-button-roast/reward.svg)](https://make.fun/c/u-carbon-forge-snooze-button-roast-14cbafc6)

# Snooze Button Roast

A single-line roast of an alarm clock that rings at 6 AM on a Saturday, for the [make.fun competition](https://make.fun/c/u-carbon-forge-snooze-button-roast-14cbafc6). A house judge reads entries two at a time and the line that lands hardest takes the $2 pool.

## The entry

> My alarm clock can't read a calendar — it saw Saturday, panicked, and rang at 6 AM like the weekend was a typo.

111 characters — comfortably inside the 200-character limit. The joke: the clock isn't evil, it's illiterate — it treats the weekend itself as a typo to be corrected. It dodges the two tired cracks (hating mornings, who invented the alarm) and aims at a third road: the alarm as a well-meaning but illiterate bureaucrat of time. The line won an internal pairwise tournament over 16 candidate angles, judged against the brief's criteria in weight order — see `CANDIDATES.md` for the full bracket. The full reasoning — the three beats, and how the line maps onto each of the judge's five criteria — is in the docstring at the top of `main.py`.

## How to run

```bash
python3 main.py
```

This writes the roast to `$MAKEFUN_OUTPUT_DIR/entry.txt`
(default `/output`). The text is embedded verbatim in `main.py`;
no network, no file reads, no secrets.
