# Superstore Sales & Profitability Analysis

## Project Overview

This project analyzes sales performance, profitability, and discount impact using the Superstore dataset.
The objective is to understand what drives revenue versus profit, identify inefficient product segments, and evaluate how discount strategies affect overall business performance.

---

## Business Questions

- Which categories and sub-categories generate the highest sales and profit?
- How do sales and profits change over time?
- Which products are profitable versus loss-making?
- How do discounts impact profit, profitability rate, and sales volume?
- Which categories and sub-categories can tolerate discounts?

---

## Methodology

- Data cleaning and inspection
- KPI calculation (Sales, Profit, Profit Margin, AOV)
- Time-series analysis (monthly trends)
- Category and sub-category analysis
- Sub-category tiering based on sales and profitability
- Discount vs. profit analysis at category and sub-category levels

---

## Key Findings

- Sales peak consistently in the second half of each year, driven mainly by higher order volume rather than higher order value.
- Technology is the strongest category in both revenue and profitability.
- Furniture generates high revenue but suffers from weak profit margins.
- Discounted transactions are significantly less profitable than non-discounted ones.
- High discounts (>30%) consistently lead to losses across all categories.
- Medium discounts are sustainable only in selected Technology and Office Supplies sub-categories.
- Sub-category tiering revealed:
  - Stars concentrated mainly in Technology
  - Hidden Potentials common in Office Supplies
  - Volume Traps dominated by Furniture (e.g., Tables)

---

## Key Recommendations

- Apply category- and sub-category–specific discount strategies instead of uniform discounting.
- Prioritize Hidden Potential sub-categories for marketing and growth, as they are already profitable but under-scaled.

---

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn