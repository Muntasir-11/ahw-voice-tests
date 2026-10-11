# Run 4: Murf, one stock voice

| | |
|---|---|
| Date | 11 October 2026 |
| Tool and plan | Murf Studio, Free plan |
| Voice | Ken (M), labelled Gen 2 and MultiNative in the app |
| Settings | Pitch 0%, speed 0%. Lines 01 to 06: language English - US & Canada, style Conversational. Lines 07 to 12: language Bangla - India, style Angry on the first pass (see below) |
| Script | `scripts/script-pack-v1.csv`, 12 lines, 1,141 characters |
| Generated and judged by | Muntasir Ahmad Chowdhury |

## Result

| Measure | Value |
|---|---|
| Lines accepted on the first take | 12 of 12 |
| Lines that needed a retake because something was read wrongly | 0 of 12 (0%) |
| Lines that failed after three takes | 0 |
| Accepted audio | 97.8 seconds (1.63 minutes) |
| Voice generation time before | 10:00 of 10 minutes available |
| Voice generation time after the first pass | 8:22 available |
| Voice generation time after the second pass | 7:32 available |
| Generation time used | 2 minutes 28 seconds |

All six English lines and all six mixed Bengali and English lines were judged correct on the first take. No words, prices, dates or brand names were logged as wrong.

## The style changed on its own

The project was set up with the style Conversational. When the block language was switched from English to Bangla - India for line 07, Murf set the style of that block to Angry, and every block added after it copied that setting. It was not noticed during the run, so lines 07 to 12 were generated and judged in the Angry style.

After the run the six mixed lines were generated a second time, in new blocks with the style set back to Conversational. No separate listening result was recorded for that second pass, so the log marks those six generations "not judged". The result above rests on the first pass.

What this means for the comparison: the judgement that the words, numbers and names were right stands. The tone of Murf's six mixed lines was not the tone used for the other tools.

## Language name

Murf's voice picker has no entry called "Bengali". A search for "Bengali" in the language list returned nothing. The language is listed as "Bangla - India".

## Cost per finished minute

Nothing was paid, because the run used the Free plan. Murf sells voice generation time, not credits. Worked out at the regular monthly price of the cheapest paid plan on the test date (Creator, $29 a month for 2 hours of voice generation, which is about $0.24 a minute):

- One pass of the 12 lines used 97.8 seconds and produced 97.8 seconds of accepted audio, so about **$0.24 per finished minute**.
- Counting the second pass as well, 2 minutes 28 seconds were used for the same 1.63 minutes of accepted audio, or about **$0.37 per finished minute**.
- On annual billing the Creator plan is $19 a month for 24 hours a year, which would be about $0.16 a minute for one pass.

## How the figures were read

- Clip lengths: each block shows its length when it is selected.
- Generation time: the counter at the top of the project.
- The app does not show when each block was generated, so the log has no clock times for this run.

## Limits of this run

- One voice and twelve short lines.
- One listener judged every take.
- The Free plan has no downloads and no commercial rights, so the audio exists only inside the Murf project.

## Evidence

- `screenshots/2026-10-10-murf-settings-and-minutes-before.jpg`
- `screenshots/2026-10-10-murf-bangla-india-voices.jpg`
- `screenshots/2026-10-10-murf-search-bengali-no-result.jpg`
- `screenshots/2026-10-11-murf-run-4-block-1-english-conversational.jpg`
- `screenshots/2026-10-11-murf-run-4-block-7-bangla-angry-style.jpg`
- `screenshots/2026-10-11-murf-run-4-block-12-minutes-after.jpg`
- `screenshots/2026-10-11-murf-run-4-block-13-bangla-conversational.jpg`
- `screenshots/2026-10-11-murf-run-4-block-18-minutes-after.jpg`
- `log/voice-test-log.csv`
