# Pennywise – Expense Tracker

A responsive React + Vite expense tracker project for managing personal income, expenses, and monthly budgets.

## Features
- Sign up and sign in screens
- Dashboard with income, expenses, and balance
- Add, edit, and delete transactions
- Expense categories
- Monthly category budgets
- Reports with income/expense comparison
- Search and filter transaction history
- Export transactions to CSV
- Browser Local Storage persistence
- Responsive layout for desktop and mobile

## Requirements
- Node.js 20.19+ or 22.12+
- npm

## Run locally
1. Download or clone this repository.
2. Open the project folder in VS Code.
3. Open the VS Code terminal.
4. Install dependencies:
   ```bash
   npm install
   ```
5. Start the development server:
   ```bash
   npm run dev
   ```
6. Open the local URL shown in the terminal (usually http://localhost:5173).

## Create a production build
```bash
npm run build
npm run preview
```

## Upload to GitHub
1. Create a new empty repository on GitHub.
2. Open this project folder in VS Code.
3. Run:
   ```bash
   git init
   git add .
   git commit -m "Initial expense tracker project"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
   git push -u origin main
   ```
4. Replace the remote URL with your repository URL.

## Important note
This is a frontend academic/demo project. Login details and transactions are stored in browser Local Storage. This is not production-grade authentication or secure cloud storage. Each browser/device has its own data. Do not use real banking passwords or sensitive financial information.
