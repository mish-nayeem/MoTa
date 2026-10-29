# Money Ledger

A personal money management app. Single file, no build step.

## Features
- **Home** – monthly earning, spending, money left, loan totals, upcoming loan returns
- **Earning** – date, amount, description, person/company
- **Expense** – Micro (type `20+300+40`, total is calculated) and Macro (rent, bills)
- **Loan** – received and given, with approx. return date, overdue tags, mark as returned
- **Project** – per-production costs by category with who paid; split equally or by percentage
- **Tasks** – placeholder, coming soon

## Run
Open `index.html` in a browser, or host it with GitHub Pages:
Settings → Pages → Deploy from branch → `main` / root.

## Data
Data is saved in the browser's localStorage, so each person's data stays on their own device and browser.
Clearing browser data deletes it. Syncing across devices or user accounts needs a backend (e.g. Firebase or Supabase).
