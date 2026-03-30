
💰 Simple Personal Finance Tracker

This is a simple command-line application written in Python to help you track your personal income and expenses. It stores transaction data in a CSV file and uses the pandas library for data manipulation and matplotlib for visualization.

✨ Features

    Add Transactions: Easily record new income or expense entries with the date, amount, category, and an optional description.

    Data Persistence: All transactions are stored in a persistent CSV file (finance_data.csv).

    View & Summarize: View a list of transactions and a summary (Total Income, Total Expense, Net Savings) within a specified date range.

    Visualization: Generate a line plot showing the trend of income and expenses over time for the selected date range.

⚙️ Prerequisites

Before running the application, you need to have Python 3 installed on your system.

The application relies on the following Python libraries:

    pandas

    matplotlib

You can install these dependencies using pip:


🚀 How to Run

    Save the files: Ensure that both main.py and data_entry.py are saved in the same directory.

    Run the script: Open your terminal or command prompt, navigate to the directory where you saved the files, and run the main script:


📝 Usage

   . Add a new transaction

Selecting 1 will prompt you for the transaction details:

    Date: Enter the date in dd-mm-yyyy format, or press Enter to use today's date.

    Amount: Enter a positive numerical value.

    Category: Enter I for Income or E for Expense.

    Description: Enter an optional description.

2. View transactions and summary within a date range

Selecting 2 will ask for a start date and an end date (dd-mm-yyyy format).

    It will display all transactions that occurred between the two dates (inclusive).

    It provides a summary: Total Income, Total Expense, and Net Savings (Income - Expense).

    It then asks if you want to see a plot. Entering y will generate a line plot comparing the daily income and expense amounts over the selected period.

3. Exit

Selecting 3 terminates the application.


📂 Data Storage

The data is saved in a file named finance_data.csv in the same directory as the Python scripts. It has the following columns:
Note: The application will automatically create this file if it doesn't exist when you add your first transaction.

(AUTHOR): MAYANK LAKHERA
          25BCY10154