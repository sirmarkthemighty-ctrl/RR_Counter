# Respiratory Rate Counter

A bedside respiratory-rate counter by Warodom Phaenthong, M.D. Tap once at the start of each breath and the rate is
worked out from the time between taps. It is one self-contained HTML page (`respiratory-rate-counter.html`, opened by
`index.html`) that runs in the browser, with no installation and no data sent anywhere.

It is a teaching aid for healthcare professionals, not a substitute for clinical judgement.

## What it does

- Rate = 60 × number of intervals ÷ seconds from the first tap to the last, updated on every tap; also the rate over the last 5 breaths.
- Interval variation (SD ÷ mean), time since the last tap, longest interval, and a 60-second progress bar.
- Breath-by-breath bar chart, undo last tap, reset, copy, and a session log of saved counts (cleared when the page closes).
- A tap more than 60 s after the last one starts a new count.
- NEWS2 respiration-rate points for adults ≥16 y (Royal College of Physicians, 2017) and WHO IMCI fast-breathing thresholds
  for children under 5. Ages 5–15 show N/A: no threshold in the app's sources.
- Keyboard: Space or Enter = breath, Backspace = undo, Esc = reset. Light and dark themes, phone layout.

Tap the version badge next to the title for the changelog.

## Licence

Copyright (c) 2026 Warodom Phaenthong, M.D. Licensed under
[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/): share and adapt for non-commercial use,
with credit, under the same licence. See `LICENSE` and `NOTICE`.
