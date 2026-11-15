# Haven Budget — Household Budget Management System

A responsive household budget web application built with HTML, CSS, JavaScript, and browser LocalStorage.

## Features
- Sign up, log in, and log out
- Each browser account has its own budget and expense records
- Set or update a monthly budget for the current month
- Add expenses with description, amount, category, and date
- Automatically calculate monthly spending and remaining balance
- View transaction history and delete expense records
- View spending totals by category
- Responsive layout for desktop and mobile

## Run the project
1. Open the `Household Budget Management System` folder in Visual Studio Code.
2. Install the **Live Server** extension (Ritwick Dey), if needed.
3. Right-click `index.html` and select **Open with Live Server**.
4. Create an account on the sign-up screen and start setting your monthly budget.

## Important storage and security note
This is a front-end academic demonstration. User accounts and budget data are stored in the browser's LocalStorage. They do not sync between devices or browsers. Clearing browser site data can erase them. The client-side login is not secure production authentication; a real public service should use a backend, database, HTTPS, server-side password hashing, and proper session management. Do not use a real or reused password.

## Project structure
- `index.html` — page structure and sign-in/sign-up screens
- `css/style.css` — responsive visual design
- `js/app.js` — account demo, monthly budget, expense records, and calculations
- `docs/` — project notes
