# Funnel Analysis – Online Retail Dataset

## Overview
This project presents a comprehensive funnel analysis conducted on an online retail transactional dataset. The analysis began with a **single-year deep dive** to establish a clear baseline of customer behavior and was later extended to a **multi-year analysis** to validate trends, uncover structural bottlenecks, and evaluate how customer behavior evolved over time.

Rather than relying on web-event data (e.g., page views or cart events), the analysis focuses on **transactional and behavioral funnels** that are appropriate for retail order data.

---

## Dataset
- Source: Online Retail Dataset (Kaggle)
- Time Period:
  - **Phase 1:** Single year of transactions
  - **Phase 2:** Multi-year transactional data
- Granularity: Invoice-level transactional data
- Key entities: Customers, Orders (Invoices), Items, Revenue

---

## Analysis Objectives
- Identify major customer drop-offs across the lifecycle
- Understand how customers translate into orders, items, and revenue
- Evaluate early-stage and long-term retention behavior
- Validate whether funnel bottlenecks persist over time
- Provide business-focused recommendations to improve conversion and retention

---

## Funnels Analyzed

### 1. Repeat Purchase Funnel  
**All Customers → Repeat Customers**

This funnel evaluates how effectively first-time buyers are converted into repeat customers.

**Key Insight:**  
While a strong majority of customers return for repeat purchases in the single-year view, the multi-year analysis confirms that **first-to-second purchase drop-off is a consistent and structural bottleneck** across years.

---

### 2. Order-Level Value Funnel  
**Customers → Orders → Items Sold → Total Revenue**

This funnel focuses on value flow rather than behavior.

**Key Insight:**  
Multi-year trends show that revenue growth is driven more by **repeat purchasing and basket expansion** than by customer acquisition alone, with revenue heavily front-loaded early in the customer lifecycle.

---

### 3. Cohort Retention Funnel  
**Month 0 → Month 1 → Month 2 → …**

A cohort-based retention funnel was built using month offsets from each customer’s first purchase.

**Key Insight:**  
The largest drop-off consistently occurs immediately after the first purchase. Multi-year cohort analysis shows that customers who return beyond the first 1–2 months tend to demonstrate **stable long-term engagement**, while newer cohorts exhibit slightly faster early churn.

---

## Key Findings (Consolidated)

### Single-Year Insights
- Early-stage churn is the primary bottleneck
- Retention within the first month is the strongest predictor of long-term value
- Existing customers contribute disproportionately to revenue

### Multi-Year Insights
- Funnel shape remains structurally consistent year-over-year
- First-to-second purchase conversion is the weakest stage across all years
- Revenue is concentrated in the first 2–3 months of the customer lifecycle
- Later cohorts show marginally faster retention decay, indicating weakening long-term loyalty

---

## Business Interpretation
- Customer acquisition strategies are effective
- Retention and repeat purchase strategies are underdeveloped
- Growth is driven more by new customers than by sustained lifetime value
- Improving early retention represents the highest-impact growth lever

---

## Business Recommendations
- Introduce post-purchase nudges within 7–14 days of first purchase
- Offer targeted repeat-purchase incentives (discounts, loyalty points, free shipping)
- Implement personalized product recommendations and bundling strategies
- Focus retention efforts on the first month, where churn is highest
- Run re-engagement campaigns for customers inactive in Months 2–3

---

## Tools & Techniques
- Python (Pandas, NumPy)
- Funnel construction using sequential business logic
- Cohort analysis and retention modeling
- Multi-year trend validation
- Business-focused interpretation of analytical results

---

## Conclusion
This analysis demonstrates that funnel performance in the online retail dataset is **structurally constrained by early-stage churn**, rather than by customer acquisition. The consistency of funnel drop-offs across multiple years confirms that retention challenges are systemic and not driven by short-term fluctuations.

By focusing on first-to-second purchase conversion and early lifecycle engagement, the business can materially improve customer lifetime value and long-term revenue without increasing acquisition spend.
