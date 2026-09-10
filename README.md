# Consumer-Goods-Ad-hoc-Insights

SQL and Power BI project analyzing AtliQ Hardware's consumer goods business and solving 10 real-world ad-hoc business requests.

## Project Overview

AtliQ Hardware is a consumer goods company that manufactures and sells computer hardware products across multiple markets and sales channels.

The management team needed faster and more actionable insights to support data-driven decision-making. This project involved solving 10 business requests using SQL and presenting the findings through business-focused insights.

The analysis covers Fiscal Years 2020 and 2021.

## Business Problem

Management identified a gap in actionable business insights, making it difficult to take quick and data-informed decisions.

To evaluate analytical and problem-solving skills, an SQL challenge was created involving 10 real-world business requests.

## Objective

The objective of this project was to:

- Solve 10 ad-hoc business requests using SQL
- Analyze sales, products, customers, discounts, and manufacturing costs
- Extract meaningful business insights from the data
- Present findings in a simple and management-friendly manner
- Provide recommendations based on the analysis

## Dataset

The dataset contains information related to:

- Customers
- Products
- Monthly sales
- Gross prices
- Manufacturing costs
- Pre-invoice deductions

The analysis uses six main tables:

- `dim_customer`
- `dim_product`
- `fact_sales_monthly`
- `fact_gross_price`
- `fact_manufacturing_cost`
- `fact_preinvoice_deductions`

## Tools & Skills Used

- MySQL
- SQL
- Power BI
- PowerPoint

### SQL Concepts Used

- JOINs
- CTEs
- Subqueries
- CASE Statements
- Aggregate Functions
- GROUP BY & ORDER BY
- Window Functions
- RANK
- DENSE_RANK

## Analysis Approach

### 1. Business Request Analysis

Reviewed the 10 ad-hoc business requests and identified the required data, calculations, and business metrics.

### 2. SQL Analysis

Created SQL queries to extract and analyze the required information from the database.

### 3. Business Insights

Converted query results into meaningful insights related to products, customers, sales, discounts, channels, and demand.

### 4. Presentation

Presented the findings in a management-friendly format using Power BI and PowerPoint.

## Key Insights

- AtliQ Exclusive operates across **8 markets in the APAC region**, showing a strong regional presence. 
- The number of unique products increased by **36.33% in 2021 compared with 2020**, indicating significant product-range expansion.
- **82.87%** of unique products belong to the **Notebook, Accessories, and Peripherals** segments.
- **Accessories** recorded the highest increase in unique products, adding **34 products** in 2021.
- **AQ HOME Allin1 Gen 2** had the highest manufacturing cost at **$240.54**, while **AQ Master wired x1 Ms** had the lowest at **$0.89**.
- **Flipkart** had the highest average pre-invoice discount at **30.83%**, followed by Viveks, Ezone, Croma, and Amazon. 
- Gross sales for **AtliQ Exclusive** dropped sharply in March 2020 to **0.4M**, followed by a strong recovery from September 2020 and a peak of **20.5M in November 2020**.
- **Q1 2020** recorded the highest total sold quantity at **7.0M units**, while Q3 declined sharply to **2.1M units**. 
- The **Retailer channel** generated the highest gross sales in FY2021, contributing **1,219.08M** or approximately **73.23%** of total gross sales.
- The **Networking & Storage (N & S)** division had the highest-selling products, with **AQ Pen Drive 2 IN 1** leading at **701.4K units**. The PC division had the lowest sales among the divisions.

## Recommendations

Based on the analysis:

1. **Focus on High-Selling Products**
   - Maintain sufficient inventory for high-demand products such as AQ Pen Drive 2 IN 1 to avoid stock shortages.

2. **Improve Low-Performing Products**
   - Analyze the reasons behind lower demand in the PC division and develop targeted marketing and product strategies.

3. **Strengthen the Retailer Channel**
   - Since retailers contribute nearly three-fourths of gross sales, the company should continue strengthening this channel while exploring opportunities in Direct and Distributor channels.

4. **Review Discount Strategies**
   - Evaluate the impact of high pre-invoice discounts and ensure discounts are aligned with sales growth and profitability objectives.

5. **Use Seasonal Opportunities**
   - Plan promotional campaigns around periods of higher demand to improve sales during weaker quarters.

6. **Expand the Product Portfolio Strategically**
   - The 36.33% increase in unique products indicates strong product expansion. Future launches should focus on segments and products with strong customer demand.

## Project Outcome

This project strengthened my ability to:

- Write SQL queries for real-world business problems
- Work with multiple related tables
- Apply advanced SQL concepts
- Analyze business performance
- Convert data into actionable insights
- Communicate findings to management
- Build a clear business story using data

## Files in this Repository

- `SQL Queries` – SQL queries used to solve the 10 business requests
- `Presentation` – Management presentation containing insights and recommendations
- `ad-hoc-requests.pdf` – Business requests provided for the SQL challenge
- `README.md` – Project documentation

## Conclusion

The project demonstrates how SQL can be used to solve real-world business problems and transform raw data into meaningful business insights.

The analysis helped identify product growth, customer discount patterns, sales trends, channel contribution, and product performance, providing useful recommendations to support better business decisions.
