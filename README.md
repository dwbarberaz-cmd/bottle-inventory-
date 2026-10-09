# Bottle Inventory — Label Scanning Upgrade

This package contains the app files for GitHub Pages. It keeps the existing browser storage key `bottleInventoryV4`, so replacing the current `index.html` on the same site should keep inventory already saved in that browser. Export a CSV backup before replacing files.

## Features
- Barcode scanning where supported by the browser.
- Label text recognition (OCR) through Tesseract.js loaded from a CDN; internet access is needed for the OCR library.
- Review and edit the suggested name, type, and size before saving. OCR guesses are not guaranteed to be correct.
- Manual bottle entry, quantity controls, search, type filter, cost and notes.
- CSV backup export and import.

## Install on GitHub Pages
1. Open the repository and make a CSV backup from the currently working app first.
2. Upload the new `index.html`, `manifest.webmanifest`, and `README.md` to the repository root, replacing files with the same names.
3. Commit the changes to the `main` branch and wait for GitHub Pages to publish.
4. Open the live site in Chrome and refresh it. Camera access requires HTTPS and permission.

Important: inventory is stored locally in the browser on the device, not in GitHub. Do not clear Chrome site data. Keep the CSV backup somewhere safe.
