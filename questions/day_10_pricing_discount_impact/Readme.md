# Day 10 — Pricing / Discount Impact Analysis

## ❓ Business Question
How do discounts impact revenue, ARPPU, and user behavior?

## 🧩 Business Context
Discounts can increase conversion but may reduce unit economics.
The business wants to understand:
- whether discounts increase total revenue,
- how discounts affect ARPPU,
- whether discounted users churn faster or behave differently.

## 📐 Assumptions & Definitions
- A **discounted transaction** is identified by `discount_amount > 0`
  (or adapt to your schema: `price < list_price`, `promo_code IS NOT NULL`, etc.).
- Metrics compared:
  - Revenue
  - Paid users
  - ARPPU
  - Transaction frequency
