 # Day 02 — Best Marketing Campaign (Quality + Revenue)

## ❓ Business Question
Which marketing campaign performs best, considering both revenue and user quality?

## 🧩 Business Context
We have multiple marketing campaigns. The business wants to scale the best ones.
“Best” should not mean only highest revenue — it should also reflect user quality, e.g. ARPPU and paid users.

## ✅ Definition of “Best” (for this analysis)
We will rank campaigns by:
1) Total revenue (scale)
2) ARPPU (quality)
3) Paid users (scale)
4) Revenue per transaction (AOV)

## 🛠 SQL (BigQuery)

### 1) Campaign leaderboard (Revenue, Paid Users, ARPPU, Transactions, AOV)
```sql
-- Replace project.dataset.table with your table name
SELECT
  campaign_id,
  campaign_name,
  SUM(revenue_amount) AS revenue,
  COUNT(DISTINCT user_id) AS paid_users,
  COUNT(*) AS transactions,
  SAFE_DIVIDE(SUM(revenue_amount), COUNT(DISTINCT user_id)) AS arppu,
  SAFE_DIVIDE(SUM(revenue_amount), COUNT(*)) AS aov
FROM `project.dataset.payments`
WHERE DATE(payment_date) BETWEEN '2025-01-01' AND '2025-03-31'
GROUP BY 1,2
HAVING paid_users >= 50
ORDER BY revenue DESC;
