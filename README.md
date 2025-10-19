# Food Mart Retail Sales Analysis

## Project Overview

This project presents a comprehensive analysis of sales performance for the `Food Mart` retail chain. The objective is to provide a 360-degree view of business operations, identify key patterns, and extract actionable insights to enable data-driven strategic decision-making.

The analysis was conducted using **Excel Power Pivot**, focusing on building a robust **Data Model**, creating advanced performance metrics with **DAX**, and designing interactive dashboards to visualize findings effectively.
---

## Key Business Questions Addressed
1. **Overall Financial Performance**

   * What are the total gross sales, net sales, net profit, and profit margin?
   * How do sales and profit trends evolve throughout the months?
   * What is the average selling price and total number of transactions?
2. **Customer Segmentation**

   * Who are our customers? (Demographic analysis by age, education, marital status, and gender)
   * Who are the Top 10 customers by sales value?
   * What are the defining characteristics of different customer segments (e.g., Elite vs. Regular)?
3. **Products & Returns Performance**

   * What are the best-selling product brands and individual products?
   * Which products have the highest return rates?
   * What is the financial impact of returns on profitability?
4. **Geographic Analysis**

   * Which stores, cities, and states perform best in terms of sales and profit?
   * Are there geographic areas with a higher concentration of customers?
---

## Technical Implementation

The project was executed in three primary phases:
### 1. Data Modeling

A **Star Schema** was implemented to ensure efficiency and ease of analysis.
The model consists of:

* **Fact Tables:** `Sales` and `Returns`
* **Dimension Tables:** `Customers`, `Products`, `Stores`, `Region`, and `Calendar`
Relationships were established between tables to ensure data integrity and proper filter propagation.

### 2. DAX Measures Creation
A suite of advanced measures was created in DAX to transform raw data into meaningful KPIs, such as:

* `[Profit Margin]`
* `[Return Rate %]`
* `[AVG Selling Price]`
* `[YoY Sales Growth %]` *(potential future enhancement)*

### 3. Interactive Dashboard Design
Three main dashboards were developed:

* **Main Dashboard:** High-level KPIs and customer segmentation insights
* **Products & Returns Dashboard:** Product performance and return analysis
* **Regions Dashboard:** Sales and profit by geography and store

---

## Tools & Technologies
* **Microsoft Excel**
  * **Power Query:** For ETL (Extract, Transform, Load) operations
  * **Power Pivot:** For data modeling and relationship management
* **DAX (Data Analysis Expressions):** For building analytical measures and KPIs
