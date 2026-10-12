# India E-Commerce Sales & Profitability Analysis Using SQL

## 1. Project Overview

This project analyzes Indian e-commerce sales data using MySQL to understand business performance, profitability, customer purchasing behavior, regional sales trends, and monthly sales target achievement.

The goal is to transform raw sales data into meaningful business insights using SQL queries.

## 2. Tools and Technologies

- MySQL
- MySQL Workbench
- SQL

## 3. Dataset

**Dataset:** Indian E-Commerce Data  
**Source:** [Kaggle — Indian E-Commerce Data](https://www.kaggle.com/datasets/benroshan/ecommerce-data)

The dataset contains three CSV files:

| Table | Description |
|---|---|
| `list_of_orders` | Order dates, customer names, states, and cities |
| `order_details` | Sales amount, profit, quantity, category, and sub-category |
| `sales_target` | Monthly sales targets for each category |

The `order_id` column connects the order information with the order details.

## 4. Business Objectives

- Measure overall sales and profitability.
- Identify the highest-performing product categories and sub-categories.
- Analyze sales and profit by state and city.
- Understand monthly sales and profit trends.
- Identify valuable customers based on sales and profit.
- Compare actual sales against monthly category targets.
- Identify low-margin product sub-categories and potential profitability issues.

## 5. SQL Skills Demonstrated

- Data exploration and quality checks
- Filtering using `WHERE`
- Aggregate functions: `SUM()`, `COUNT()`, `AVG()`, `MIN()`, and `MAX()`
- Grouping using `GROUP BY`
- Filtering grouped results using `HAVING`
- Table joins using `INNER JOIN`
- Subqueries
- Conditional logic using `CASE WHEN`
- Date conversion and formatting
- Calculated columns and profit margin analysis
- Sorting and limiting results using `ORDER BY` and `LIMIT`

## 6. Key Performance Indicators (KPIs)

The following overall metrics were calculated during the analysis:

| KPI | Result |
|---|---:|
| Total Sales | ₹431,502 |
| Total Profit | ₹23,955 |
| Total Quantity Sold | 5,615 |
| Unique Orders | 500 |
| Average Order Value | Approximately ₹863 |
| Overall Profit Margin | Approximately 5.55% |

## 7. Key Findings

### Category Performance

- Electronics generated the highest sales, at ₹165,267.
- Clothing generated ₹139,054 in sales.
- Furniture generated ₹127,181 in sales.
- Furniture had the lowest profit margin among the three categories, at approximately 1.81%.

### Sales Target Analysis

- A total of 36 month-category combinations were evaluated.
- 16 combinations achieved or exceeded their sales targets.
- 20 combinations missed their sales targets.
- Approximately 44.44% achieved their targets, while 55.56% missed them.

### Profitability Analysis

Sub-category and regional analyses were performed to compare sales, total profit, and profit margins and to identify areas requiring further investigation.

## 8. Business Recommendations

1. **Improve furniture profitability:** Review pricing, discounts, and product costs to understand the category's low profit margin.
2. **Investigate missed targets:** Examine the months and categories with the largest target shortfalls to identify possible causes.
3. **Monitor profitability alongside sales:** High revenue does not necessarily mean high profit.
4. **Study high-performing categories:** Identify successful products and sales patterns that could inform business decisions.
5. **Review regional performance:** Compare sales and profit margins across states and cities before making regional investment decisions.
6. **Track customer value:** Use customer-level sales and profit analysis to understand purchasing behavior.

## 9. Project Files

- `india_ecommerce_sales_analysis.sql` — SQL queries for data analysis.
- `README.md` — Project documentation, objectives, findings, and recommendations.

## 10. Conclusion

This project demonstrates how SQL can be used to analyze e-commerce data, calculate business KPIs, compare product and regional performance, evaluate customer value, and measure sales target achievement.

The analysis provides a foundation for data-driven decisions related to sales growth and profitability improvement.

---

**Project Domain:** E-Commerce Analytics  
**Database:** MySQL  
**Project Type:** Data Analytics Portfolio Project
