# Business Questions → SQL Answers

A collection of **daily, business-driven SQL analyses** designed to demonstrate
how real-world business questions can be translated into **structured analysis,
clear metrics, and actionable insights**.

All analyses are implemented using **BigQuery SQL** and focus on
**revenue, product, retention, and marketing analytics**.

---

## 🎯 Project Goal

This project simulates the **day-to-day work of a Data Analyst / Product Analyst**:
- ambiguous business questions,
- metric definition and decomposition,
- cohort and lifecycle thinking,
- decision-oriented insights.

The emphasis is on **analytical thinking**, not just writing SQL queries.

---

## 📂 Project Structure

questions/

├── day_01_revenue_drop.md

├── day_02_best_campaign.md

├── day_03_lowest_retention_segment.md

├── day_04_funnel_bottleneck.md

├── day_05_new_vs_returning_users.md

├── day_06_revenue_concentration_pareto.md

├── day_07_churned_revenue.md

├── day_08_arppu_drivers.md

├── day_09_reactivated_users.md

├── day_10_pricing_discount_impact.md

├── day_11_cohort_revenue.md

├── day_12_ltv_by_cohort.md

├── day_13_stickiness_active_payers.md

├── day_14_marketing_attribution_first_last.md

├── day_15_executive_summary.md


Each file represents **one complete analytical case**.

---

## 📊 Covered Topics (Days 1–15)

### Revenue & Monetization
- Revenue decomposition and MoM drops
- ARPPU drivers
- Revenue concentration (Pareto / power users)
- Pricing and discount impact

### Retention & Lifecycle
- D30 retention by segment
- Funnel bottleneck analysis
- Churned revenue (lost money, not just users)
- Reactivated users and recovered revenue

### Cohorts & Long-Term Value
- Cohort revenue analysis
- LTV by cohort
- Early vs long-term cohort performance

### Engagement & Stickiness
- DAU / WAU / MAU proxy using active payers
- Stickiness trends over time

### Marketing Analytics
- Best campaign / segment quality
- First-touch vs last-touch attribution

---

## 🧠 Executive Summary

For a management-ready overview of insights and recommendations, see:

👉 **`questions/day_15_executive_summary.md`**

This file summarizes:
- key revenue drivers,
- retention and churn risks,
- pricing and marketing implications,
- strategic recommendations.

---

## 🛠 Tools & Techniques

- SQL (BigQuery)
- CTEs and window functions
- Cohort analysis
- Funnel analysis
- Revenue and lifecycle metrics
- Attribution logic

---

## 🚀 Why This Project

This repository demonstrates:
- how analysts think beyond dashboards,
- how SQL supports business decisions,
- how to communicate insights clearly to stakeholders.

The format is intentionally **concise, iterative, and realistic** —
similar to internal analytics requests in real companies.

---

## 🔜 Next Steps (Optional)
- Convert selected cases into **Tableau / Power BI dashboards**
- Extend cohort analysis with **CAC vs LTV**
- Add attribution variants (time-decay, linear)
- Continue daily analytical cases
  - cohort analysis,
  - pricing sensitivity,
  - marketing attribution.
