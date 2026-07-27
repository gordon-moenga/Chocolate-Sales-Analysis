# Chocolate Sales Analysis (2022–2023)

## Project Overview

This project analyzes a chocolate sales dataset to uncover sales trends, evaluate business performance, and generate actionable business insights. The analysis follows a complete data analytics workflow, beginning with data understanding and cleaning, followed by exploratory data analysis (EDA), and ending with the development of an interactive Power BI dashboard.

The project demonstrates practical data analysis skills using Python for data preparation and exploration, and Power BI for business reporting and visualization.

---

## Project Objectives

- Understand the structure and quality of the dataset.
- Clean and prepare the data for analysis.
- Analyze sales performance across different business dimensions.
- Identify trends, patterns, and relationships within the data.
- Develop an interactive Power BI dashboard to present key business insights.

---

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
