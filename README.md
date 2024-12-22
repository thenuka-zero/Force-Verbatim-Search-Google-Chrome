# Force Verbatim Mode on Google Search - Chrome Extension 🔍

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

> A Chrome extension that automatically enables Verbatim mode for all your Google searches.

## 🚀 What it does

This extension ensures that every Google search you perform uses Verbatim mode, which:
* Forces exact keyword matching
* Removes word variations and synonyms
* Removes news results
* Disables location-based result customization
* Prevents automatic spelling corrections

## 💡 Why use it?

When you need precise search results, Google's default behavior of including variations and synonyms can be frustrating. This extension:
* Saves time by eliminating the need to manually enable Verbatim mode
* Ensures consistent search behavior across all your queries
* Helps find exact phrases and specific terms without unwanted variations
* Particularly useful for technical searches, programming queries, and research

## 📦 Installation

1. Download the extension files:
   ```
   - manifest.json
   - background.js
   - icon128.png
   ```
2. Open Chrome and navigate to `chrome://extensions/`
3. Enable "Developer mode" using the toggle in the top-right corner
4. Click "Load unpacked"
5. Select the folder containing the extension files

## ⚙️ How it works

The extension runs in the background and automatically adds the Verbatim mode parameter (`tbs=li:1`) to all Google search URLs. It's lightweight and only activates on Google search pages.

## 🔒 Permissions

This extension requires minimal permissions:
* `webNavigation`: To detect when you perform a Google search
* Access to Google domains: To modify search URLs

## 🤝 Contributing

Feel free to submit issues and pull requests with improvements.

## 📄 License

[MIT](https://choosealicense.com/licenses/mit/) - Feel free to modify and reuse this code.

---
Created by [Thenuka](https://github.com/Thenuka)
