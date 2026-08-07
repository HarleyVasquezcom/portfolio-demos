# Ledger — Personal Finance

A clean, light "fintech" personal-accounting app: log income and expenses, track monthly budgets, and see where your money goes. Fully client-side with localStorage persistence.

## Features

- Transactions with date, note, category and signed amount (positive = income, negative = expense)
- Complete CRUD via a table with inline modal editing and delete
- Global balance + per-month income / expense / net summary with a month switcher
- CSS `conic-gradient` donut of spending by category for the selected month, with hover budget popovers
- Income vs expenses bars across the last 12 months (pure DOM, no canvas)
- Per-category budgets against current spending, editable inline
- Filters by category and month, plus free-text note/category search
- CSV export and a one-click reset to the demo dataset
- localStorage persistence under the `ledger-app-v1` key with a `try/catch` fallback
- Light "fintech" theme: white-on-`#f8fafc` cards, emerald + violet accents, tabular numerals, sticky header
- Accessible: labeled controls, visible focus, real form submit, amount validation (> 0)
- Single-file, no dependencies, no external assets

## Run

```bash
vercel --prod
```