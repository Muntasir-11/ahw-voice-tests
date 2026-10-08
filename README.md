# AHW voice tests

Test records behind the voice-tool tests published on [AI Hustle World](https://aihustleworld.com).

## What this is

The same 12 short script lines are run through each voice tool. Every attempt is logged, including the ones that were rejected. The scripts, the log and dated screenshots are kept here so that anyone can check the numbers quoted in the articles.

The audio files are not published. The tests are run on free plans, and ElevenLabs' free plan does not include a commercial licence, so the clips stay offline with the founder.

## The script pack

`scripts/script-pack-v1.csv` holds the 12 lines: six in English and six in mixed Bengali and English, the way a creator in Dhaka speaks. Each line targets one thing voice tools often get wrong: a brand name, a price with numbers, a date and time, a question, an emotional line, and a web address with abbreviations.

The lines are plain text with no tags or markup, so they can be pasted into any tool unchanged.

## Rules for a run

1. One tool, one voice, one model and one group of settings for all 12 lines.
2. Each line is generated once, then listened to.
3. A take is rejected if a word is mispronounced, if a number, price or date is read wrongly, if the brand name is wrong, if an English or Bengali word is spoken with the wrong language's sounds, or if there is an audible glitch.
4. A rejected line is generated again with the same text and settings, up to three takes. If the third take fails, the line is logged as failed.
5. Every take gets one row in `log/voice-test-log.csv`, accepted or not.
6. A screenshot of the credit balance is taken before and after each run.

## The numbers we report

- **Credits used:** the balance before the run minus the balance after.
- **Retake rate:** the lines that needed more than one take, divided by 12.
- **Cost per finished minute:** nothing was paid for a free-plan run, so this figure is worked out. It is the credits used in the run, retakes included, multiplied by the price per credit of the cheapest paid plan on the test date, and divided by the minutes of accepted audio. The plan's regular monthly price is used, not a first-month discount.

## Who does what

Muntasir Ahmad Chowdhury, founder of AI Hustle World, generates and listens to every take and decides whether it passes. The scripts, the log template and the arithmetic were prepared with AI assistance.

## Folders

| Folder | Contents |
|---|---|
| `scripts/` | The script pack |
| `log/` | One row per take |
| `screenshots/` | Dated screenshots of settings and credit balances |

## Runs

| Run | Tool | Plan | Status |
|---|---|---|---|
| 1 | ElevenLabs, Eleven v4, stock voice | Free | Not run yet |
