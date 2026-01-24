# Funnel Analysis – Online Retail Dataset (Single-Year Study)

## Overview
This project presents a comprehensive funnel analysis conducted on an online retail transactional dataset covering **one year of customer activity**. The goal of the analysis was to identify key drop-off points in the customer lifecycle, understand how revenue is generated, and uncover actionable opportunities to improve conversion and retention.

Rather than relying on web-event data (e.g., page views or cart events), the analysis focuses on **transactional and behavioral funnels** that are appropriate for retail order data.

---

## Dataset
- Source: Online Retail Dataset (Kaggle)
- Time Period: **Single year of transactions**
- Granularity: Invoice-level transactional data
- Key entities: Customers, Orders (Invoices), Items, Revenue

---

## Analysis Objectives
- Identify major customer drop-offs across the lifecycle
- Understand how customers translate into orders, items, and revenue
- Evaluate early-stage and long-term retention behavior
- Provide business-focused recommendations to improve conversion

---

## Funnels Analyzed

### 1. Repeat Purchase Funnel  
**All Customers → Repeat Customers**

This funnel evaluates how effectively first-time buyers are converted into repeat customers, highlighting early churn and retention opportunities.

**Key Insight:**  
While a strong majority of customers return for repeat purchases, a meaningful portion churns after their first transaction, making early engagement critical.

---

### 2. Order-Level Value Funnel  
**Customers → Orders → Items Sold → Total Revenue**

This funnel focuses on value flow rather than behavior, showing how customer volume translates into business outcomes.

**Key Insight:**  
Revenue growth is driven more by repeat purchasing and basket expansion than by customer acquisition alone.

---

### 3. Cohort Retention Funnel  
**Month 0 → Month 1 → Month 2 → …**

A cohort-based retention funnel was built using month offsets from each customer’s first purchase to track repeat behavior over time.

**Key Insight:**  
The largest drop-off occurs immediately after the first purchase. Customers who return beyond the first month tend to exhibit stable, long-term engagement.

---

## Key Findings (Summary)
- Early-stage churn is the primary bottleneck across funnels
- Retention within the first month is the strongest predictor of long-term value
- Existing customers contribute disproportionately to revenue
- Improving early retention can significantly increase customer lifetime value

---

## Business Recommendations
- Introduce post-purchase nudges and reminders shortly after first purchase
- Offer targeted repeat-purchase incentives (discounts, loyalty points, free shipping)
- Use cross-sell and bundling strategies to increase basket size
- Focus retention efforts on the first month, where churn is highest

---

## Tools & Techniques
- Python (Pandas, NumPy)
- Cohort analysis and retention modeling
- Funnel construction using sequential business logic
- Business-focused interpretation of analytical results

---

## What’s Next 🚀
This analysis was conducted on **a single year of data** to establish a clean and interpretable baseline.  
A **multi-year funnel and cohort analysis** is planned next to examine trends over time, cohort evolution, and long-term changes in customer behavior.

*More coming soon 👀*
