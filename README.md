# 📱 FINORA — Track Your Expenses
### Personal Finance Tracker App · IT2010 Mobile Application Development · SLIIT 2025

![Kotlin](https://img.shields.io/badge/Kotlin-Android-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Android](https://img.shields.io/badge/Android%20Studio-3DDC84?style=for-the-badge&logo=androidstudio&logoColor=white)
![SLIIT](https://img.shields.io/badge/SLIIT-Year%202%20Sem%202-3B82F6?style=for-the-badge&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-34d399?style=for-the-badge)

---

## 📌 Overview

**Finora** is an innovative personal finance management application built in **Kotlin** for Android. Designed for students, professionals, freelancers, and anyone seeking financial clarity — Finora provides real-time expense tracking, smart budgeting, savings goals, and visual financial insights without the complexity of traditional tools.

> *"Financial transparency and autonomy — directly in your hands."*

---

## ✨ Features

### Core Features
| Feature | Description |
|---------|-------------|
| **Transaction Management** | Add, edit, and delete income/expense transactions with title, amount, category, and date |
| **Category-wise Analysis** | Categorize transactions (Food, Transport, Bills, Entertainment, etc.) with per-category summaries |
| **Monthly Budget Setup** | Set monthly budgets with real-time progress tracking and overspending warnings |
| **Data Persistence** | SharedPreferences for currency, budget settings, and transaction history across restarts |

### Bonus Features
| Feature | Description |
|---------|-------------|
| **Data Backup** | Export transaction data as text/JSON file via Internal Storage; restore from backup |
| **Push Notifications** | Budget alert notifications when approaching or exceeding monthly limit via Android NotificationManager |
| **Daily Reminders** | Optional reminders to log daily expenses |

---

## 📱 App Screens

| Screen | Description |
|--------|-------------|
| **Login Page** | Secure user authentication |
| **Home Screen** | Dashboard overview of income, expenses, and balance |
| **Transactions** | Full transaction history with add/edit/delete |
| **Budget Setup** | Monthly budget configuration with progress indicator |
| **Dashboard** | Visual charts and spending analytics |
| **Settings** | Currency, notifications, and app preferences |
| **Profile** | User profile and account management |

---

## 🛠️ Tech Stack

| Technology | Usage |
|-----------|-------|
| **Kotlin** | Primary programming language |
| **Android Studio** | IDE and development environment |
| **XML Layouts** | UI design with focus on simplicity |
| **SharedPreferences** | User preferences and transaction history persistence |
| **Internal Storage** | Backup and restore functionality |
| **Android NotificationManager** | Budget alerts and reminders |

---

## 🏗️ Architecture

```
FINORA App
├── Authentication
│   └── Login / Sign Up
├── Dashboard
│   ├── Balance Overview
│   ├── Spending Charts
│   └── Budget Progress
├── Transactions
│   ├── Add Transaction
│   ├── Edit Transaction
│   ├── Delete Transaction
│   └── Category Filter
├── Budget Management
│   ├── Set Monthly Budget
│   ├── Progress Tracking
│   └── Overspend Alerts
├── Data Layer
│   ├── SharedPreferences (settings + history)
│   └── Internal Storage (backup/restore)
└── Notifications
    ├── Budget Limit Alerts
    └── Daily Expense Reminders
```

---

## 📊 Evaluation

| Criteria | Marks |
|----------|-------|
| Functionality — Core & bonus features | 4 |
| Creativity & Usability — UI/UX design | 2 |
| Validation & Error Handling | 2 |
| Data Persistence — SharedPreferences & Internal Storage | 2 |
| **Total** | **10** |

---

## 📁 Repository Structure

```
finora-finance-tracker/
├── README.md
├── app/
│   ├── src/main/
│   │   ├── java/com/finora/
│   │   │   ├── MainActivity.kt
│   │   │   ├── LoginActivity.kt
│   │   │   ├── DashboardActivity.kt
│   │   │   ├── TransactionActivity.kt
│   │   │   ├── BudgetActivity.kt
│   │   │   ├── ProfileActivity.kt
│   │   │   └── NotificationHelper.kt
│   │   └── res/
│   │       ├── layout/          ← XML UI layouts
│   │       ├── values/
│   │       │   ├── strings.xml
│   │       │   └── colors.xml
│   │       └── drawable/
├── screenshots/
│   ├── login.png
│   ├── home.png
│   ├── transactions.png
│   ├── budget.png
│   ├── dashboard.png
│   └── settings.png
└── report/
    └── IT2010_Lab03_IT23224384.pdf
```

---

## 🚀 Getting Started

### Prerequisites
- Android Studio (latest version)
- Android SDK API 24+
- Kotlin plugin enabled

### Run Locally
```bash
# Clone the repository
git clone https://github.com/RanushiAmanda/finora-finance-tracker.git

# Open in Android Studio
File → Open → select the project folder

# Run on emulator or physical device
Run → Run 'app' (Shift + F10)
```

---

## 📋 Module Details

- **Module:** IT2010 — Mobile Application Development
- **Assessment:** Lab Exam 03 — CA Component 3
- **Year:** 2nd Year, Semester 2 · 2025
- **Batch:** Y2.S2.WE.IT.03.02
- **Institute:** Sri Lanka Institute of Information Technology (SLIIT)
- **Faculty:** Faculty of Computing

---

## 👩‍💻 Developer

**Ranushi Amanda** · IT23224384

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ranushi%20Amanda-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ranushi-amanda-b135572ba)
[![GitHub](https://img.shields.io/badge/GitHub-RanushiAmanda-100000?style=flat&logo=github&logoColor=white)](https://github.com/RanushiAmanda)
[![Blog](https://img.shields.io/badge/Blog-InsightForge-FF5722?style=flat&logo=blogger&logoColor=white)](https://ranu001coding.blogspot.com)

---

> *"Finora removes the necessity for spreadsheets or complicated tools — allowing users to enhance their savings, curb excessive spending, and maintain financial oversight effortlessly."*
