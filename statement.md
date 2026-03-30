# 📄 Project Statement: Simple Personal Finance Tracker

## 🎯 Problem Statement

Tracking personal income and expenses is crucial for effective **budgeting** and achieving **financial awareness**. Many existing solutions are either too complex, require paid subscriptions, or are inaccessible to users who prefer a straightforward, local, and open-source approach.

The problem this project addresses is the need for a **simple, free, and command-line based tool** that allows users to easily:
1.  **Record** their daily financial transactions (income and expenses).
2.  **View** historical transaction data within a specific time frame.
3.  **Analyze** their spending habits by providing clear summaries and visual trends.

---

## 🧭 Scope of the Project

The scope of this project is limited to developing a **Command Line Interface (CLI)** application for basic personal finance tracking using Python.

### Included in Scope:
* **Data Management:** Implementing classes to initialize, read, and write transaction data to a **local CSV file** (`finance_data.csv`).
* **Transaction Logging:** Functionality to input and log transactions, including date, amount, category (Income/Expense), and description.
* **Reporting:** Generating a report (text output) showing all transactions and a summary (Total Income, Total Expense, Net Savings) within a user-defined date range.
* **Data Visualization:** Generating a basic line plot using `matplotlib` to show Income and Expense trends over the specified date range.
* **User Interface:** A simple, text-based menu for navigating the application functions.

### Excluded from Scope:
* Integration with external bank accounts or APIs.
* Advanced budgeting features (e.g., setting monthly limits, forecasting).
* A graphical user interface (GUI) or web interface.
* Data encryption or sophisticated security features.

---

## 👥 Target Users

The primary target users for this application are individuals who:

* **Beginner Users:** Are new to financial tracking and need a simple tool without complex features or onboarding.
* **Command Line Enthusiasts:** Prefer or are comfortable interacting with applications via the command line.
* **Students/Developers:** Need a free, open-source tool for managing their basic personal finances or want a simple project to learn about data manipulation with Python/Pandas.
* **Privacy-Focused Users:** Prefer to keep their financial data stored **locally** rather than on cloud-based services.

---

## ✨ High-Level Features

| Feature Category | Description |
| :--- | :--- |
| **Transaction Recording** | Allows users to **add new entries** (income or expense) with validation for date, amount, and category. |
| **Date-Range Query** | Enables viewing all recorded transactions and generating a comprehensive **financial summary** (Income, Expense, Net Savings) for any specified period. |
| **Data Persistence** | Transactions are reliably saved to and read from a **`finance_data.csv`** file, ensuring data is not lost between sessions. |
| **Visualization** | Generates a simple **time-series plot** to visually track and compare daily income versus daily expenses. |
| **User Prompts** | Provides clear, interactive **prompts** to guide the user through data entry and menu navigation. |