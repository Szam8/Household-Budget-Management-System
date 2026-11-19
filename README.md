# Haven Budget — Household Budget Management System

A clean, responsive React household finance app for recording income and expenses, setting a monthly budget, and viewing summaries.

## Features
- React + Vite application
- Responsive dashboard and separate Overview, Transactions, Budgets, Reports, and Settings pages
- Add, edit, delete, search, and filter transactions
- Income and expense calculations in Philippine pesos (PHP)
- Monthly budget tracking and expense category breakdown
- CSV export
- Browser localStorage persistence
- Installable Progressive Web App (PWA) foundation
- Sign-up and sign-in form with password strength checks

## Requirements
- Node.js LTS (includes npm)
- Visual Studio Code
- Git and Git Bash (for GitHub commits)


## Website name and URL
- Website name: **Haven Budget**
- Local development URL: **http://localhost:5173/**
- This is a local development address. To get a public URL, deploy the project to a hosting service such as Vercel or Netlify and connect your GitHub repository.

## Install as a phone app
The project includes a web app manifest and service worker. For a production PWA, deploy it over HTTPS, then open the deployed website in a supported browser and choose **Install app** or **Add to Home screen**. Play Store publication is a separate process: package the PWA (for example, with a Trusted Web Activity), prepare store assets, create a Play Console developer account, and satisfy current Google Play policies.

## Important security and data note
This is a school-project prototype. Authentication is client-side and demo passwords are stored in browser localStorage. It is **not safe for real financial or personal data** and does not provide server-side authentication, password hashing, database backups, or multi-device sync. A production release needs a secure backend, HTTPS, password hashing (such as Argon2id or bcrypt), server-side validation, authorization, and privacy/security testing. Do not reuse a real password here.

## Project structure
```text
Household-Budget-Management-System/
├── public/
│   ├── icon.svg
│   ├── manifest.webmanifest
│   └── sw.js
├── src/
│   ├── App.jsx
│   ├── main.jsx
│   └── styles.css
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

## Testing checklist
- [ ] Sign up using a test email and a strong test password.
- [ ] Log out and log in again.
- [ ] Add one income transaction and one expense transaction.
- [ ] Confirm the dashboard totals update.
- [ ] Edit and delete a transaction.
- [ ] Search and filter transaction records.
- [ ] Change the monthly budget and verify the remaining amount.
- [ ] Export transactions to CSV.
- [ ] Refresh the page and confirm demo data remains in the same browser.
- [ ] Test mobile layout using browser developer tools.

