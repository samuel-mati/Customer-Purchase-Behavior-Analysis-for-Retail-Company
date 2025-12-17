# Customer Shopping Behavior Analysis  
### SQL Portfolio Project

**Author:** Samuel Mati  
**Role:** Data Alchemist | Business Analyst  
**Date:** 6th December 2025  

---

## 1. Executive Summary

A retail company observed changes in customer purchasing behavior across demographics, product categories, and engagement patterns. To support data-driven decision-making, I conducted an end-to-end customer behavior analysis using SQL to evaluate revenue drivers, loyalty patterns, discount effectiveness, shipping preferences, and subscription impact.

The analysis revealed that **male customers generated 157,890 in revenue**, more than double that of **female customers at 75,191**. **Young adults** emerged as the highest-value age group, contributing **70,899 in revenue across 1,173 orders**. Additionally, **non-subscribed customers generated 170,436 in revenue**, nearly three times the revenue of subscribed customers (**62,645**), despite having similar average purchase values.

These insights provide clear opportunities to improve marketing targeting, optimize discount usage, refine the subscription model, and strengthen customer retention strategies.

![Dashboard](src/Dashboard.png)

### Key Highlights
- Identified revenue gaps across **gender, age groups, and subscription status**
- Found **discount-dependent products** with discount usage rates exceeding **47%**
- Revealed a highly loyal customer base with **3,116 customers making 10+ purchases**
- Highlighted **young adults** as the most valuable revenue segment

---

## 2. Business Problem

The company wants to better understand customer shopping behavior to improve sales performance, customer satisfaction, and long-term loyalty. Management observed changes in purchasing patterns across demographics, product categories, and customer engagement factors such as discounts, shipping preferences, and subscriptions.

### Central Business Question

**How can consumer shopping data be leveraged to identify trends, improve customer engagement, and optimize marketing and product strategies?**

This project uses SQL-based analysis to transform raw transaction data into actionable business intelligence for marketing, sales, and customer experience teams.

---

## 3. Methodology

### Analytical Approach

An end-to-end customer behavior analysis was performed using transactional retail data.  
Key performance indicators (KPIs) were defined and analyzed, including:

- Total Revenue
- Average Purchase Amount
- Discount Usage Rate
- Product Review Ratings
- Customer Loyalty Segmentation
- Subscription Revenue Contribution
- Revenue by Demographics

The primary deliverable is a structured SQL analysis answering real-world business questions.

### Technical Implementation

- **Data Exploration:** Inspected table structure and data quality using SQL queries
- **Aggregation & Grouping:** Used `SUM`, `AVG`, and `COUNT` to analyze revenue and customer behavior
- **Conditional Logic:** Applied `CASE WHEN` statements for segmentation and classification
- **Subqueries:** Compared individual purchase behavior against overall averages
- **Window Functions:** Used `RANK()` to identify top-performing products by category
- **CTEs:** Applied Common Table Expressions for clean, modular analysis

All analysis was performed entirely using SQL.

---

## 4. Skills & Tools Used

### Tools
- SQL (MySQL / PostgreSQL-compatible syntax)

### SQL Techniques Applied
- `GROUP BY`, `ORDER BY`
- `SUM`, `AVG`, `COUNT`
- `CASE WHEN`
- Subqueries
- Window Functions (`RANK`)
- Common Table Expressions (CTEs)

### Business Concepts Applied
- Revenue Analysis
- Customer Segmentation
- Discount Effectiveness
- Product Performance Analysis
- Subscription Impact Assessment
- Demographic Revenue Contribution

---

## 5. Key Results & Insights

### Revenue by Gender
- Male customers: **157,890**
- Female customers: **75,191**
- Revenue difference: **82,699**

### Product Ratings
- Gloves: **3.9**
- Sandals: **3.8**
- Boots: **3.8**
- Hats: **3.8**
- Skirts: **3.8**

### Shipping Type & Spending
- Express shipping average spend: **60.48**
- Standard shipping average spend: **50.50**
- Difference: **9.98 higher** for express shipping

### Subscription Impact
- **Subscribed customers**
  - Customers: **1,053**
  - Average spend: **59.49**
  - Revenue: **62,645**

- **Non-subscribed customers**
  - Customers: **2,847**
  - Average spend: **59.87**
  - Revenue: **170,436**

### Discount-Driven Products
- Hats: **50.00%**
- Sneakers: **49.66%**
- Coats: **49.07%**
- Sweaters: **48.17%**
- Pants: **47.37%**

### Customer Loyalty Segmentation
- New customers (1 purchase): **83**
- Returning customers (2–10 purchases): **701**
- Loyal customers (10+ purchases): **3,116**

### Top Products by Category
**Accessories**
- Jewelry: **171**
- Sunglasses: **161**
- Belt: **161**

**Clothing**
- Blouse: **171**
- Pants: **171**
- Shirt: **169**

**Footwear**
- Sandals: **160**
- Shoes: **150**
- Sneakers: **145**

**Outerwear**
- Jacket: **163**
- Coat: **161**

### Repeat Buyers & Subscriptions
- Subscribed repeat buyers (>5 purchases): **958**
- Non-subscribed repeat buyers (>5 purchases): **2,518**

### Revenue by Age Group
- Young Adults: **70,899 revenue**, **1,173 orders**
- Middle-Aged: **59,197 revenue**, **986 orders**
- Seniors: **55,763 revenue**, **944 orders**
- Adults: **47,222 revenue**, **797 orders**

---

## 6. Business Recommendations

1. **Improve Female Customer Revenue**
   - Launch targeted campaigns to close the **82,699 revenue gap**.

2. **Optimize the Subscription Model**
   - Redesign subscription incentives to increase value beyond current spending levels.

3. **Refine Discount Strategy**
   - Reduce heavy discounting on products with discount usage above **47%** to protect margins.

4. **Leverage Loyal Customers**
   - Focus retention efforts on the **3,116 loyal customers** to maximize lifetime value.

5. **Target High-Value Age Groups**
   - Prioritize marketing spend on **young adults**, the highest revenue-generating segment.

---

## 7. Next Steps (Future Enhancements)

- Advanced loyalty scoring and behavioral segmentation
- Time-series analysis for seasonal trends
- Integration with Power BI or Tableau for automated reporting
- Customer Lifetime Value (CLV) modeling
- End-to-end automated analytics pipelines

---

## 8. Repository Contents

- SQL analysis scripts
- Project documentation
- Power BI dashboard
- Supporting files and assets

---

*This project demonstrates the ability to translate raw transactional data into clear, actionable business insights using SQL.*
