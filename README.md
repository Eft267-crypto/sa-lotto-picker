# SA Lotto Picker 🎰

A one-page app that generates 5 lines for **Lotto**, **Daily Lotto** or **PowerBall**. The lines are based on patterns in recent South African draws.

**Open the app:** https://eft267-crypto.github.io/sa-lotto-picker/

## How it works
1. **Choose game:** Lotto (6 from 1–52), Daily Lotto (5 from 1–36) or PowerBall (5 from 1–50 + PB 1–16).
2. **Generate my 5 lines.** Every line must pass these rules, which come from recent draws:
   - 1–2 hot numbers and 1 cold number
   - the odd/even and low/high mix seen most often in recent draws
   - a line total in the usual range
   - at least one single-digit number
   - never an exact past winning line
   - no two lines share more than 2 numbers
   - PowerBall: a bonus ball of 1–10, favouring 5 and 10

The **"Test it"** section replays past draws and compares pattern lines with random lines.

## Data
- PowerBall: all 2026 draws (main, Plus and XTRA). Long-term number frequencies go back to 2009.
- Lotto: draws from October 2025 to October 2026. The number range returned to 1–52 on 3 June 2026.
- Daily Lotto: recent draws, plus number frequencies from 2019 to 2026.

To refresh the pattern, add new results to the `RAW` data at the top of the script in `index.html`.

## Disclaimer
Lottery draws are random. No app can predict or guarantee winning numbers. 18+ only. Play responsibly. Helpline: 0800 006 008.
