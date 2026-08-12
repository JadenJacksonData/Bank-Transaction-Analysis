# Bank Transaction Analysis

## Project Overview

This project analyzes bank transaction data using SQL to identify transaction patterns, cash-flow trends, monthly activity, and account-level behavior.

The goal of the analysis was to answer business questions about deposits, withdrawals, transaction activity, and account performance.

---

## Business Questions

1. What is the total transaction volume and value?
2. How do deposits compare with withdrawals?
3. Which month had the highest transaction activity?
4. Which month had the highest deposit and withdrawal activity?
5. Which account generated the highest transaction value?
6. How concentrated is transaction activity across accounts?
7. How frequently did accounts transact?

---

## Dataset

The dataset contains bank transaction records with the following fields:

- `transaction_id` — Unique identifier for each transaction
- `account_id` — Identifier for the account
- `transaction_date` — Date of the transaction
- `transaction_type` — Deposit or Withdrawal
- `amount` — Dollar amount of the transaction

### Dataset Summary

- 50 total transactions
- 25 unique accounts
- 25 deposits
- 25 withdrawals
- $95,600 total transaction value

---

## Tools & Technologies

- SQL
- SQLite
- DB Browser for SQLite
- GitHub

---

## Analysis

### 1. Overall Transaction Performance

The analysis found:

- 50 total transactions
- $95,600 total transaction value
- $1,912 average transaction amount

---

### 2. Deposit vs. Withdrawal Analysis

Deposits totaled $77,400, representing 81% of total transaction value.

Withdrawals totaled $18,200, representing 19% of total transaction value.

Both transaction types occurred 25 times, but deposits averaged $3,096 compared with $728 for withdrawals.

This means deposits averaged approximately 4.25 times the value of withdrawals.

---

### 3. Monthly Analysis

March was the strongest month for transaction activity.

- $29,750 total transaction value
- 14 transactions
- 31.12% of total transaction value
- $24,200 in deposits
- $5,550 in withdrawals

March represented the highest month for both deposits and withdrawals.

---

### 4. Account Analysis

There were 25 unique accounts and each account recorded two transactions.

Account number 1025 generated the highest total transaction value at $8,800.

Of Account 1025's activity:

- $7,000 was deposited
- $1,800 was withdrawn

Account 1025 represented 9.2% of total transaction value, indicating that overall activity was relatively diversified across accounts.

---

## Key Findings

- The account generated a $59,200 net positive cash flow.
- Deposits represented 81% of total transaction value.
- Deposits averaged 4.25 times the value of withdrawals.
- March was the highest-activity month.
- March generated $29,750 in total transaction value.
- Account 1025 had the highest transaction value at $8,800.
- Transaction frequency was evenly distributed, with each account recording two transactions.
- No single account represented a large majority of total transaction activity.

---

## Business Insights

The analysis indicates a strong positive cash-flow position driven primarily by larger incoming deposits rather than a higher frequency of transactions.

March's high activity suggests a period of increased financial movement and may warrant additional investigation into the factors contributing to the monthly increase.

The relatively even distribution of transaction frequency across accounts indicates that differences in account value were driven by transaction size rather than transaction frequency.

---

## Conclusion

The bank transaction analysis revealed a strong overall financial position, with deposits significantly exceeding withdrawals and generating a net positive cash flow of $59,200. Deposits were substantially larger on average, while March was the highest-activity month for both deposits and withdrawals. Transaction frequency was evenly distributed across the 25 accounts, and no single account represented a large share of total activity.

Overall, this project demonstrates how SQL can be used to analyze financial data, identify transaction patterns, evaluate cash-flow trends, and generate business insights that can support informed decision-making.

---

## SQL Skills Demonstrated

- SELECT
- WHERE
- GROUP BY
- ORDER BY
- COUNT
- SUM
- AVG
- MIN
- MAX
- DISTINCT
- Date/string manipulation with `SUBSTR`
- Aggregation
- Business-oriented data analysis
