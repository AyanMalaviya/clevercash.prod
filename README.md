# CleverCash - Personal Finance & Expense Tracker App

![CleverCash Header](https://via.placeholder.com/1200x400.png?text=CleverCash+-+Smart+Finance+Management)

**CleverCash** is a powerful, offline-first personal finance management application built with React Native. It helps you track expenses, manage budgets, log incomes, and monitor active IOUs—all from a beautiful, lightning-fast dashboard. 

Whether you are looking to manage your monthly budget, track where your money goes with AI-assisted categorization, or settle debts with friends, CleverCash is your all-in-one financial ledger.

[![Download APK](https://img.shields.io/badge/Download-Android_APK-green?style=for-the-badge&logo=android)](https://github.com/AyanMalaviya/CleverCash.prod/releases/latest)
[![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)]()
[![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)]()

## 📱 Features

*   **📊 Deep Analytics:** Visualize your spending trends over 7, 30, or 365 days with interactive Pie and Line charts.
*   **🤖 AI Categorization:** Auto-guess transaction categories based on titles to save you time.
*   **🤝 IOU Tracker:** Never forget who owes you money. Track debts and split bills effortlessly.
*   **🏦 Multi-Account Management:** Keep separate ledgers for your Bank, Cash, and Credit accounts.
*   **📸 Receipt Scanner:** Attach physical receipt photos directly to your digital transactions.
*   **🔒 Offline-First & Private:** Your financial data is securely stored locally using SQLite. No cloud syncing required.

## 🚀 Download & Install

You can install CleverCash directly on your Android device:

1. Go to the [Releases Page](https://github.com/AyanMalaviya/CleverCash.prod/releases).
2. Download the latest `CleverCash.apk` file.
3. Open the file on your Android phone and click **Install**. *(You may need to allow installation from unknown sources in your settings).*

## 📸 Screenshots

| Dashboard Overview | Adding an Expense | Spending Analytics |
| :---: | :---: | :---: |
| <img src="https://via.placeholder.com/250x500.png?text=Dashboard" width="200"/> | <img src="https://via.placeholder.com/250x500.png?text=Add+Expense" width="200"/> | <img src="https://via.placeholder.com/250x500.png?text=Analytics" width="200"/> |

## 🛠️ Tech Stack

This project is an excellent example of modern mobile app development using:
*   **Framework:** React Native / Expo
*   **UI Library:** React Native Paper
*   **Database:** SQLite (Offline Storage)
*   **Data Visualization:** React Native Gifted Charts
*   **Analytics:** PostHog

## 💻 Running Locally (For Developers)

Want to contribute or run the app from source? 

```bash
# Clone the repository
git clone [https://github.com/AyanMalaviya/CleverCash.prod.git](https://github.com/AyanMalaviya/CleverCash.prod.git)

# Navigate into the directory
cd CleverCash.prod

# Install dependencies
npm install

# Start the Expo server
npx expo start
