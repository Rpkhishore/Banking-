🏦 BankWise: A Mini Banking SQL Project
📌 Project Overview:
A SQL-based banking system using MySQL, designed with relational database structure, foreign key constraints, and advanced SQL operations. This project simulates customer banking operations including accounts, transactions, loans, and more.

🧱 Modules / Tables Involved:
Customers – Customer personal data

Accounts – Account types, balances, dates

Transactions – Credit/Debit entries

Loans – Loan info, due dates, amounts

Cards – Debit/Credit card management

Branches – Branch names & locations

Transaction_Log – Trigger-based log table

🔗 Relationships:
Customers ➡️ Accounts (1:N)

Accounts ➡️ Transactions (1:N)

Customers ➡️ Loans (1:N)

Customers ➡️ Cards (1:N)

Branches ➡️ Accounts & Loans

All with foreign keys, to simulate real-world normalized schema.

🧪 Dataset:
Over 200+ rows of fake banking data

Includes NULL values for practical data cleaning

Used realistic fields like Aadhaar masked IDs, IFSC, balance, card numbers, etc.

⚙️ Advanced SQL Concepts Used:
✅ JOIN, INNER JOIN, LEFT JOIN, FULL JOIN
✅ GROUP BY, HAVING, CASE, IN, EXISTS
✅ RANK() and ROW_NUMBER() for analytical ranking
✅ TRIGGERS for auto-logging large transactions
✅ INDEX for performance on account_id and date fields
✅ VIEWS for cleaner analytics
✅ IS NULL, IFNULL(), COALESCE() for data cleaning
