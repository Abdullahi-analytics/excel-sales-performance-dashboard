# Excel Sales Performance Dashboard

## Project Overview

This project presents an end-to-end sales performance analysis and interactive dashboard developed in Microsoft Excel.

The project started with an original sales dataset containing inconsistencies and data-quality issues. I worked through the process of cleaning and validating the data, creating analytical calculations, building PivotTables and KPIs, and developing a dashboard to communicate business performance clearly.

The objective was not simply to create a visually appealing dashboard, but to use the available data to understand sales performance, profitability, trends, and areas that may require business attention.

## Business Objective

The analysis was designed to help answer key business questions such as:

* How much revenue and profit did the business generate?
* What is the overall profit margin?
* Which categories and products contribute most to revenue and profit?
* Which cities generate the highest sales?
* How does sales performance change over time?
* Which payment methods are most frequently used?
* Are high-revenue products also highly profitable?
* Are there data-quality issues that could affect business reporting?

## Tools & Skills

* Microsoft Excel
* Data Cleaning & Preparation
* Data Validation
* Excel Formulas
* PivotTables
* PivotCharts
* KPI Development
* Data Analysis
* Data Visualization
* Dashboard Development
* Business Insights & Recommendations

## Data Preparation

The original dataset was reviewed and prepared before analysis.

Key data preparation activities included:

* Identifying missing and inconsistent values
* Standardizing text fields
* Reviewing duplicate or inconsistent order identifiers
* Validating order and shipping dates
* Checking numeric fields
* Creating calculated fields for sales and profitability
* Preparing the dataset for PivotTable and dashboard analysis

A separate original-data sheet was retained to distinguish the source data from the cleaned analytical dataset.

## Key Calculations

The analysis included several calculated metrics.

### Gross Sales

**Gross Sales = Quantity Sold × Unit Price**

### Discount Amount

**Discount Amount = Gross Sales × Discount %**

### Revenue

**Revenue = Gross Sales − Discount Amount**

### Total Cost

**Total Cost = Quantity Sold × Unit Cost**

### Profit

**Profit = Revenue − Total Cost**

### Profit Margin

**Profit Margin = Total Profit ÷ Total Revenue × 100**

## Key Performance Indicators

The dashboard summarizes the following overall performance metrics:

| KPI           |  Result |
| ------------- | ------: |
| Total Revenue | ₦43.25M |
| Total Profit  |  ₦9.37M |
| Profit Margin |  21.66% |
| Total Orders  |      49 |
| Units Sold    |     591 |

## Analysis Performed

### Category Performance

Revenue and profitability were analyzed across the different product categories to understand which categories contribute most to sales and profit.

### Product Performance

Products were analyzed based on revenue, profit, and quantity sold to identify differences between sales volume and profitability.

### City Performance

Sales performance was analyzed across cities to identify major revenue-contributing markets and areas with lower sales contribution.

### Monthly Performance

Monthly revenue and profit were reviewed to identify changes and trends in sales performance over the analyzed period.

### Payment Method Analysis

Payment methods were analyzed to understand transaction distribution and revenue contribution across different payment channels.

## Key Business Insights

### 1. Overall Profitability

The business generated approximately ₦43.25M in revenue and ₦9.37M in profit, resulting in an overall profit margin of approximately 21.66%.

This shows that profitability should be monitored alongside revenue when evaluating business performance.

### 2. Electronics Revenue Contribution

Electronics generated approximately ₦23.78M in revenue, representing roughly 55% of total revenue.

However, its profit contribution was only moderately higher than Accessories despite its substantially higher revenue. This highlights the importance of evaluating profitability rather than relying on revenue alone.

### 3. Accessories Profitability

Accessories generated approximately ₦9.27M in revenue and ₦3.33M in profit, giving the category an estimated profit margin of about 36%.

This indicates that a category with a smaller revenue contribution can still make a significant contribution to overall profitability.

### 4. City Performance

Lagos generated approximately ₦14.56M in revenue, representing about 33.7% of total revenue.

This indicates a significant concentration of sales in Lagos compared with the other cities analyzed.

### 5. Product Performance

Laptops generated the highest product revenue at approximately ₦11.72M. However, Monitors generated approximately ₦1.60M in profit compared with approximately ₦1.28M from Laptops despite having lower revenue.

This demonstrates that high revenue does not necessarily mean the highest profitability.

## Data Quality Findings

The analysis identified three transactions where the recorded shipping date occurred before the order date.

These records represent approximately ₦4.15M in revenue.

This finding demonstrates the importance of validating source data before using it for operational or management decisions.

## Business Recommendations

Based on the analysis, the following actions could be considered:

1. Review pricing, discounting, and cost structures within Electronics to identify opportunities for improving profitability.

2. Explore cross-selling and product-bundling opportunities for Accessories, particularly alongside Electronics purchases.

3. Investigate the factors contributing to Lagos' strong performance and assess whether relevant patterns can be applied to other markets.

4. Review the pricing and cost structure of high-revenue products such as Laptops to better understand their profitability.

5. Strengthen data-validation processes, particularly for order and shipping dates, to improve reporting reliability.

## Dashboard Preview

![Sales Performance Dashboard](screenshots/lms-dashboard.png)

## Project Structure

```text
excel-sales-performance-dashboard/
│
├── README.md
├── Sales_Performance_Dashboard.xlsx
│
├── screenshots/
│   └── dashboard.png
│
└── documentation/
    └── project-notes.md
```

## Project Outcome

This project demonstrates my ability to take a raw dataset through the analytical process of:

**Raw Data → Data Cleaning → Data Validation → Analysis → KPI Development → Visualization → Business Insights**

The project also strengthened my understanding that effective data analysis is not only about producing dashboards. It is about asking the right questions, validating the data, interpreting the results, and communicating findings in a way that can support better business decisions.

## Author

**Abdullahi Muhammed Soliu**

Data/BI Analyst

Skills: Excel | SQL | Power BI | Python | Power Query | DAX

Open to Data Analyst, Business Intelligence Analyst, Business Analyst, and Reporting Analyst opportunities.

---

*This project was developed as part of my continued practice and growth in Data Analytics.*
