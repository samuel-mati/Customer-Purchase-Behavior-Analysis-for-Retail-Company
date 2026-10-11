# MEMORANDUM

**TO:** Retail Operations Manager

**FROM:** Samuel Mati,  Business Analyst

**DATE:** 6th December 2025

**RE:** Customer Shopping Behavior Analysis - Findings & Recommended Actions

---

## Purpose

A request was made to investigate shifts in customer purchasing behavior and identify where we can improve sales performance, engagement, and loyalty. I conducted an end-to-end analysis of our transactional retail data using SQL, examining revenue drivers, discount effectiveness, shipping preferences, subscription impact, and customer loyalty. Below are the results and the actions I recommend.

---

## What the Data Revealed

**1. Revenue is heavily skewed by gender.**
Male customers generated **157,890** in revenue versus **75,191** from female customers - a gap of **82,699**. This is our single largest untapped revenue opportunity.

**2. Young adults are our highest-value segment.**
Young adults contributed **70,899** in revenue across **1,173 orders**, outpacing middle-aged (59,197), senior (55,763), and adult (47,222) segments.

**3. The subscription model is underperforming.**
Non-subscribed customers generated **170,436** in revenue — nearly **3x** the **62,645** from subscribers — despite nearly identical average spend (59.87 vs. 59.49). The problem is volume, not value per customer.

**4. Discounting is eroding margins on key products.**
Several products show discount usage rates exceeding **47%**: Hats (50.00%), Sneakers (49.66%), Coats (49.07%), Sweaters (48.17%), and Pants (47.37%).

**5. We have a strong loyalty base to leverage.**
**3,116 customers** have made 10+ purchases — a highly loyal segment we can build retention strategies around.

**6. Express shipping correlates with higher spend.**
Express shipping customers spend **60.48** on average versus **50.50** for standard — a **9.98** difference worth exploring as an upsell driver.

---

## Recommended Actions

| # | Action | Expected Impact |
|---|--------|-----------------|
| 1 | Launch targeted marketing campaigns to close the **82,699** gender revenue gap | Increase female customer revenue |
| 2 | Redesign subscription incentives to grow subscriber volume | Convert non-subscribers; grow recurring revenue |
| 3 | Reduce discounting on the five products with 47%+ discount rates | Protect margins on high-volume items |
| 4 | Build retention programs around the **3,116 loyal customers** | Maximize lifetime value from proven buyers |
| 5 | Prioritize marketing spend on **young adults** | Capitalize on highest-revenue segment |

---

## Next Steps

I recommend we proceed with advanced loyalty scoring, time-series analysis for seasonal trends, and integration with Power BI/Tableau for automated reporting. I can also build a Customer Lifetime Value (CLV) model to sharpen targeting further.

Happy to walk through the full SQL analysis and dashboard at your convenience.

---

*Analysis performed entirely in SQL. Full scripts, documentation, and Power BI dashboard available in the project repository.*
