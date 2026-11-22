# Krillion Answer Atlas

Krillion Answer Atlas is a Tampermonkey userscript that shows answer suggestions for the current [Krillion](https://krillion.io/) prompt. Use it in solo games or Puffer Party to see rarity, pick an answer, and save the result in your browser.

The downloadable **Krillion answer library** contains **163,423 saved answers**. The panel labels confirmed rarity, estimates, and unrated entries so you can see what the game has verified.

[Install the userscript](https://raw.githubusercontent.com/Airl1ke/krillion-answer-atlas/main/krillion-answer-atlas.user.js) · [Download 163,423 saved answers](https://raw.githubusercontent.com/Airl1ke/krillion-answer-atlas/main/krillion-163423-answers.json)

## Install with Tampermonkey

1. Install and enable [Tampermonkey](https://www.tampermonkey.net/) in the browser you use to play.
2. Open [Install Krillion Answer Atlas](https://raw.githubusercontent.com/Airl1ke/krillion-answer-atlas/main/krillion-answer-atlas.user.js) and choose **Install** or **Update** in Tampermonkey.
3. Open or refresh [krillion.io](https://krillion.io/). Look for the **Krillion Answer Atlas** panel. If it is hidden, open the Tampermonkey menu on the game tab and select **Show Krillion Answer Atlas on screen**.

## Moving from Krillionare or Krillion Helper

Before switching, open **Memory → Export JSON** in the old panel to save your personal collection. Disable the old script in Tampermonkey, install Krillion Answer Atlas, then open **Memory → Import JSON** in Krillion Answer Atlas and select your export. Review your preferences in **Settings** and **Party controls**.

## Import the answer library

1. Save [krillion-163423-answers.json](https://github.com/Airl1ke/krillion-answer-atlas/raw/refs/heads/main/krillion-163423-answers.json) to your computer. If your browser shows the JSON as text, use **Save page as** and keep the `.json` extension.
2. In the helper, open **Memory → Import JSON**, choose the file, and wait for **Import complete**. Importing merges the library with your existing answers.
3. Open **Answers** during a round to see suggestions. New results are saved in Tampermonkey in that browser. Use **Memory → Export JSON** to back up your collection.

## Puffer Party

Under **Answers**, enable **Party auto-answer** if you want the helper to play. Open **Party controls → Answering** for mimic typing, lowercase entry, and panic retries. **Rooms & queue** contains the rated and unrated queue options. You can adjust the reading pace and typing speed under **Settings**.

## Credits

This version builds on [YourAverageCow’s Krillion Helper](https://github.com/YourAverageCow/krillion-helper). The embedded VT323 font includes its license in the userscript. Offline word suggestions use the [ENABLE dictionary](https://github.com/dolph/dictionary) and compound spellings adapted from [Christina Gagné’s dataset](https://doi.org/10.17632/yyvb36r574.1) under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
