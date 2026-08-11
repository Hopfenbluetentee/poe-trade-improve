# poe-trade-improve

A small Tampermonkey script to improve the trade website experience of Path of Exile.

It adds a compact bar above the search filters on
`https://www.pathofexile.com/trade/search/*`, mirroring the filters you reach for
most often so you do not have to scroll through the filter panel for them.

## Installation

The script needs a userscript manager to run. These instructions use
[Tampermonkey](https://www.tampermonkey.net/). Install the extension first, then
the script itself.

### 1. Install Tampermonkey

**Firefox**

1. Open [Tampermonkey on addons.mozilla.org](https://addons.mozilla.org/firefox/addon/tampermonkey/).
2. Click **Add to Firefox**, then confirm with **Add**.

**Chrome**

1. Open [Tampermonkey on the Chrome Web Store](https://chromewebstore.google.com/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo).
2. Click **Add to Chrome**, then confirm with **Add extension**.
3. Chrome only runs userscripts once they are explicitly allowed. Open
   `chrome://extensions`, find Tampermonkey, open **Details** and enable
   **Allow User Scripts**. On older Chrome versions there is no such switch —
   enable **Developer mode** at the top right of `chrome://extensions` instead.

**Other browsers**

Tampermonkey is also available for Edge, Safari, Opera and others. See the
[official Tampermonkey site](https://www.tampermonkey.net/) for the matching
download, and the [Tampermonkey FAQ](https://www.tampermonkey.net/faq.php) if
anything behaves differently there.

### 2. Install the script

1. Open the raw script file:
   **[poe-trade-improve.user.js](https://github.com/Hopfenbluetentee/poe-trade-improve/raw/refs/heads/main/poe-trade-improve.user.js)**
2. Tampermonkey recognises the `.user.js` address and opens its own install
   page instead of showing the source. Click **Install**.
3. Reload any open Path of Exile trade tab.

If you get a wall of source code rather than the install page, Tampermonkey is
either not installed or not enabled — check step 1 first.

## Updates

The script carries an update URL, so Tampermonkey checks for new versions on its
own and offers them like any other extension update. To force a check, open the
Tampermonkey dashboard, switch to **Installed userscripts** and use **Check for
userscript updates**.

## License

[MIT](LICENSE)
