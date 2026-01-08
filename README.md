# Business Questions → SQL Answers

This repository contains daily analytical case studies that translate real business questions into structured SQL analysis using **BigQuery**.

Each case focuses on:
- understanding the business problem,
- selecting the right metrics,
- writing clear and efficient SQL,
- producing actionable business insights.

The goal is to demonstrate **analytical thinking**, not just technical SQL skills.

---


## 📂 Project Structure

questions/
├── day_01_revenue_drop.md
├── day_02_best_campaign.md
├── day_03_lowest_retention_segment.md
├── day_04_funnel_bottleneck.md
├── day_05_new_vs_returning_users.md


Each file represents **one complete business problem**.

---

## ✅ Covered Business Questions (Days 1–5)

### Day 01 — Revenue Drop Investigation
**Question:** Why did revenue drop month-over-month?  
**Focus:**
- Revenue decomposition
- Paid users vs ARPPU
- Segment contribution analysis

---

### Day 02 — Best Marketing Campaign
**Question:** Which campaign performs best considering both scale and quality?  
**Focus:**
- Revenue vs ARPPU trade-offs
- Paid users
- Balanced ranking logic

---

### Day 03 — Lowest Retention Segment
**Question:** Which user segment has the lowest D30 retention?  
**Focus:**
- Retention logic
- Early churn detection
- Segment-level analysis

---

### Day 04 — Funnel Bottleneck Analysis
**Question:** Where do users drop off the most in the conversion funnel?  
**Focus:**
- Funnel construction
- Conversion rates
- Drop-off analysis by segment

---

### Day 05 — New vs Returning Users
**Question:** Who drives revenue: new users or returning users?  
**Focus:**
- Revenue split by lifecycle stage
- ARPPU comparison
- Dependency on acquisition vs retention

---

## 🛠 Tools & Technologies
- SQL (BigQuery)
- Analytical metrics: Revenue, ARPPU, Retention, Funnel Conversion
- Window functions, CTEs, segmentation logic

---

## 🎯 Why This Project
This repository simulates the **day-to-day work of a Data Analyst**, including:
- ambiguous business questions,
- metric definition,
- trade-off analysis,
- decision-oriented insights.

Each case is intentionally concise and focused, similar to real analytical requests from stakeholders.

---

## 🚀 Next Steps
- Continue adding **one business question per day**
- Expand into:
  - revenue concentration (Pareto),
  - churned revenue,
  - cohort analysis,
  - pricing sensitivity,
  - marketing attribution.
