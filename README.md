# Mera-Hisaab

[[https://hatchable.com/deploy-button.svg]](https://hatchable.com/deploy?repo=https://github.com/Ayushkumar6161/Mera-Hisaab)

**Mera-Hisaab** is a personal finance, expense, and wallet tracker built as a fast, offline-ready Progressive Web App (PWA) with cloud account sync. Track daily expenses, Cash & UPI balances, split bills, savings, and get/borrow records across phone and desktop.

## Features

- **Dashboard & Analytics:** Monthly overview with spending breakdowns, trends, and mini calendar.
- **Expenses & Transaction History:** Add, search, filter, edit, and delete daily expenses with undo support.
- **Cash & UPI Wallet:** Track Cash and UPI balances separately with wallet transfers.
- **Money Received & Savings:** Log income, parent/extra money, and monthly savings.
- **Get / Borrow & Split:** Keep separate records for money to receive/return and split expenses with friends.
- **Reports & Exports:** Visual reports plus **Excel**, **PDF**, and **JSON Backup/Restore** exports.
- **Installable App (PWA):** Install directly on Android, iOS, and Desktop with offline app-shell caching and Dark/Light mode.

## Tech Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript, PWA (`manifest.webmanifest`, Service Worker)
- **Backend:** Hatchable Serverless APIs (`/api/account/*`, `/api/data`, `/api/profile`)
- **Database:** PostgreSQL (`app_accounts`, `expense_data`, `expense_data_backups`, `user_profiles`)

## Install as an App

- **Browser (Android / Desktop / iOS):** Open the app, click **Install App** in the sidebar or Settings, and add it to your Home Screen.
- **Android APK:** Use the `android-app` + GitHub Actions workflow in this repository or [PWABuilder](https://www.pwabuilder.com/) to package an `.apk`.

## Author

Built by **Ayush Kumar** ([@Ayushkumar6161](https://github.com/Ayushkumar6161)) on [Hatchable](https://hatchable.com).
