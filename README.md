# Pocket Ledger

A small, responsive expense tracker that runs in your browser. Add an expense, choose a category, and see monthly, weekly, and lifetime totals at a glance.

## Features

- Add and delete expenses
- Categorize entries and filter the list
- View spending totals for this month, this week, and all time
- Store entries in browser local storage; no account or server required
- Responsive layout for desktop and mobile

## Run it

Open [index.html](index.html) in a modern browser. No install or build step is needed.

## Data and privacy

Expenses are saved in local storage in the browser where you opened the app. They are not sent to a server. Clearing that browser's site data removes the saved entries, and entries do not automatically sync between devices.

## Currency

The display uses Indian rupees (INR). To use another currency, change the `currency` option in the `money()` function in `index.html`.

## License

MIT
