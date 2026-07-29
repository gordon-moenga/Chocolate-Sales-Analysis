# Chocolate Sales Analysis

## Project Overview

The company seeks to improve its sales performance by gaining a deeper understanding of how its products, markets and sales channels contribute to overall business success. This project analyses two years of historical chocolate sales data (2022–2023) to evaluate business performance across products, countries, sales channels and sales representatives. The analysis focuses on identifying the primary drivers of revenue, shipment volume and sales performance, enabling stakeholders to make informed decisions regarding product strategy, market opportunities and operational efficiency.

Methodology: A structured workflow was followed, covering data preparation, analysis and dashboard development.

Data Cleaning: The dataset was cleaned by resolving missing values, correcting data types and improving data quality.

Exploratory Data Analysis: Sales trends, patterns and relationships were explored using statistical analysis and visualisations.

## Business Understanding

The company aims to strengthen its sales strategy by understanding the factors that influence business performance. By analysing two years of historical sales data, the analytics team evaluates product performance, regional sales, sales channels and revenue trends to identify opportunities that support informed business decisions and sustainable growth.

## Key Business Questions

Revenue Performance: How has the company's revenue performed over the two-year analysis period?

Product Performance: Which products contribute the most to overall business performance?

Market Performance: Which countries and sales channels generate the highest sales?

Sales Performance: How effectively are sales representatives and marketing efforts driving revenue?

## Goal

Increase revenue by identifying the highest-performing products and markets.

Optimise sales strategies by evaluating the performance of sales channels and sales representatives.

Improve operational planning by understanding sales trends and shipment volumes.

Support strategic decision-making through interactive dashboards and business insights.

## Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Power BI

---

## Project Workflow

### 1. Data Understanding

The dataset was explored to understand its structure and identify potential data quality issues.

Tasks completed:
- Loaded the dataset
- Inspected the dataset structure
- Reviewed data types
- Checked missing values
- Checked duplicate records
- Generated descriptive statistics

---

### 2. Data Cleaning

The dataset was cleaned to ensure accurate and reliable analysis.

Tasks completed:
- Converted the `Order_Date` column to datetime format
- Converted the `Amount` column to a numeric data type
- Removed rows containing missing values
- Verified data consistency
- Prepared the dataset for analysis

---

### 3. Exploratory Data Analysis (EDA)

The cleaned dataset was analyzed to answer important business questions.

Business questions explored:

- What is the overall sales performance?
- Which products generate the highest revenue?
- Which countries contribute the most revenue?
- Which sales channels perform best?
- Who are the top-performing salespeople?
- How does revenue change over time?
- What is the distribution of order revenue?
- Is there a relationship between marketing spend and revenue?

Visualizations created:

- Revenue by Product
- Revenue by Country
- Revenue by Sales Channel
- Top 10 Salespeople by Revenue
- Monthly Revenue Trend
- Revenue Distribution
- Marketing Spend vs Revenue

---

### 4. Power BI Dashboard

The cleaned dataset was imported into Power BI to create an interactive business dashboard.

Dashboard features include:

- Executive KPI Cards
- Revenue by Product
- Revenue by Country
- Revenue by Sales Channel
- Monthly Revenue Trend
- Top Salespeople Analysis
- Interactive Filters and Slicers

---

## Key Insights

- The company generated approximately **USD 101.75 million** in total revenue.
- Retail was the highest-performing sales channel, followed by Wholesale and Online.
- December recorded the highest monthly revenue during the analysis period.
- Revenue distribution was positively skewed, with many low-to-medium value orders and fewer high-value transactions.
- Marketing spend showed a moderate positive correlation (0.373) with revenue, indicating that while marketing contributes to sales performance, other business factors also influence revenue.

---

## Project Structure

```text
Chocolate-Sales-Analysis/
│
├── data/
│   ├── Chocolate_Sales.csv
│   └── Chocolate_Sales_Cleaned.csv
│
├── notebooks/
│   └── Data_Cleaning_and_EDA.ipynb
│
├── powerbi/
│   └── Chocolate_Sales_Dashboard.pbix
│
├── images/
│   ├── Executive_dashboard.png
│   ├── Sales_performance_dashboard.png
│
├── README.md
```

---

## Skills Demonstrated

- Data Cleaning
- Data Wrangling
- Exploratory Data Analysis
- Business Analytics
- Statistical Analysis
- Data Visualization
- Dashboard Development
- Business Intelligence
- Python Programming
- Power BI Reporting

---
