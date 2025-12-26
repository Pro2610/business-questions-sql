# Day 01 — Revenue Drop Investigation (MoM)

## ❓ Business Question
Why did revenue drop in March compared to February?

## 🧩 Business Context
The business noticed a month-over-month (MoM) revenue decline in March.  
We want to understand whether the drop was driven by:
- fewer paid users,
- lower average revenue per paid user (ARPPU),
- fewer transactions,
- changes in a specific country / software / user type segment.

## 🛠 SQL (BigQuery)

### 1) Confirm the revenue drop (Feb vs Mar)
```sql
-- Replace project.dataset.table with your table name
SELECT
  FORMAT_DATE('%Y-%m', DATE(payment_date)) AS month,
  SUM(revenue_amount) AS revenue
FROM `project.dataset.payments`
WHERE DATE(payment_date) BETWEEN '2025-02-01' AND '2025-03-31'
GROUP BY 1
ORDER BY 1;
