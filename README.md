## How to install (developer / local)

1. Extract the `BetterChrome.zip` to a folder.
2. Open Chrome and visit `chrome://extensions/`.
3. Enable **Developer mode** (toggle in the top-right).
4. Click **Load unpacked** and select the `BetterChrome.zip` folder (the folder that contains `manifest.json`).
5. Open a new tab to view the custom new tab page.

**To update during development:** edit files in the folder, then click **Reload** on the `chrome://extensions/` card for this extension.

**To create a distributable ZIP:**

- macOS / Linux:
```bash
zip -r chrome-customizer-extension.zip chrome-customizer-extension
