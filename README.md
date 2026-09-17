# PESONAL_FINANCE_ANALYTICS
📊 Personal Finance Analytics Dashboard
An interactive Excel-based personal finance tracker and analytics dashboard that turns 1,000+ raw bank/credit-card transactions into a clean, slicer-driven dashboard for tracking income, expenses, and net cash flow.

🎯 Purpose

This project was built to practice turning raw, transaction-level financial data into an actionable analytics dashboard — the same workflow used in real-world personal budgeting tools and business finance reporting.
Specifically, it aims to:
Track income vs. expenses over time to understand overall cash flow health
Break spending down by category, payment method, and account to spot where money actually goes

📁 Project Structure

personal-finance-dashboard/
├── Personal_Finance_Dataset.xlsx     # Raw transaction data (1,000 rows)
├── Personal_Finance_Dashboard.xlsx   # Pivot tables + interactive dashboard
├── dashboard-preview.png             # Dashboard screenshot
└── README.md

✨ Features

1.KPI summary cards — Total Income, Total Expense, and Net Cash Flow at a glance
2.Monthly Income vs Expense — year-over-year comparison bar chart
3.Expense by Category — donut chart (Dining, Groceries, Rent, Transport, Utilities, etc.)
4.Expense by Payment Method — Auto-Pay, Cash, Check, Credit, Debit, Direct Deposit, Transfer
5.Income by Source — Salary vs Freelance
6.Expense by Account — Checking, Credit Card, Savings (pie chart)
7.Top 10 Expense Merchants — biggest spend destinations
8.Interactive slicers — filter the entire dashboard by Account (Checking / Credit Card / Savings) and Type (Income / Expense)
9.One-click Reset button to clear all filters

🚀 How to Use

1.Download both .xlsx files.
2.Open Personal_Finance_Dashboard.xlsx to explore the dashboard, or Personal_Finance_Dataset.xlsx to view/edit the raw transactions.
3.Use the Account and Type slicers on the dashboard to filter the view.
4.To refresh the dashboard after editing the dataset, copy the updated data into the dataset file, then reconnect it as the pivot table source and click Refresh 5.All in Excel's Data tab.
6.Click Reset on the dashboard to clear all active filters.

🧠 What I Learned

1.Structuring flat transaction data for PivotTable analysis
2.Building PivotTables & PivotCharts from a shared data source
3.Designing a clean, single-screen dashboard layout with KPI cards
4.Using slicers to filter multiple charts at once
5.Separating raw data from the reporting/dashboard layer
