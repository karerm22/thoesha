# Kareem — Personal Finance & Savings

A responsive Arabic RTL personal finance dashboard with a daily savings journal. Static HTML/CSS/JavaScript; no framework, no API key, no server required.

## Features
- Editable personal display name (starts as Kareem).
- Daily income, expenses, net balance, multiple income sources and custom categories.
- Savings goals with target amount, deadline, amount already saved, progress percentage, and daily amount needed.
- Daily savings deposits per goal with date and note; savings journal and deposit deletion that adjusts the goal balance.
- Recent transactions, searchable and filterable transaction history.
- Weekly cash-flow chart, six-month chart, monthly category breakdown, custom date range report.
- Local browser storage, JSON export/import backup, responsive dark UI.
- All UI is in Arabic and RTL; values shown in EGP.

## Run locally
Open `index.html` in a modern browser, or run:
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000`.

## Publish on GitHub Pages
1. Create a public GitHub repository, e.g. `kareem-finance`.
2. Upload the contents of this folder into the repository root (`index.html`, `style.css`, `app.js`, `favicon.svg`, `README.md`).
3. Open **Settings → Pages**.
4. Choose **Deploy from a branch**, branch `main`, folder `/(root)`, then **Save**.
5. Wait for deployment; the URL will look like `https://YOUR-USERNAME.github.io/kareem-finance/`.

## Important storage note
The app stores data in the browser's `localStorage` on the current device/browser. It does not sync across devices. Export a JSON backup regularly from **الإعدادات والبيانات**. Clearing browser data or using private browsing may remove the stored data. Do not enter bank card numbers, passwords, or other sensitive information.

## Files
- `index.html`: page structure and dialogs
- `style.css`: responsive dark design
- `app.js`: calculations, savings journal, reports, and local persistence
- `favicon.svg`: app icon
