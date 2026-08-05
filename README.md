# Chocolate Sales Analysis

## Overview

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

## Data Source

[data/Chocolate_Sales.csv](https://www.kaggle.com/datasets/arjunmehta1992/chocolate-sales-in-20222023): Shows Sales Information, Product Information, Market Information, and Sales Performance Information.

## Tools & Technologies

**Python** – Data cleaning, transformation and exploratory data analysis.

**Pandas & NumPy** – Data manipulation, analysis and numerical computation.

**Matplotlib** – Data visualisation and trend analysis.

**Jupyter Notebook** – Data preparation, analysis and project documentation.

**Power BI** – Interactive dashboard development and business reporting.

**Power Query** – Data validation and preparation for reporting.

## Data Preparation
The dataset underwent a structured preparation process to ensure it was accurate, consistent and suitable for analysis and dashboard development.
### Data Loading
- Imported the chocolate sales dataset into Jupyter Notebook using Pandas.
- Loaded the dataset for cleaning, analysis and visualisation.

### Data Inspection
- Reviewed the dataset structure, column names and data types.
- Identified missing values, duplicate records and data quality issues.

### Handling Missing Values
- Identified missing values across the dataset.
- Addressed missing values using appropriate data cleaning techniques.

### Data Cleaning
- Removed duplicate records.
- Corrected data types for date and numerical columns.
- Converted monetary values into numerical format.
- Standardised data formats for consistency.
- Investigated and handled invalid shipment records.

### Data Integration
- Exported the cleaned dataset as a CSV file.
- Imported the cleaned dataset into Power BI for dashboard development.

## Final Data
Following data preparation, the final dataset contained all the key business attributes required for analysis and reporting, including: Order ID, Product, Country, Sales Channel, Salesperson, Order Date, Discount Percentage, Price per Box, Marketing Spend, Boxes Shipped and Revenue (Amount).

## Data Analysis and Visualization
After preparing the data, several analyses and visualisations were conducted to extract insights into the company's sales performance. The main focus was on revenue performance, product performance, market performance and sales performance.

<img width="1090" height="444" alt="image" src="https://github.com/user-attachments/assets/9788f86b-10f4-4b9c-9b47-acb44ccf4d8e" />

**Insight:** 
December recorded the highest monthly revenue, followed by November, and January. June had the lowest revenue.
The results suggest that sales fluctuate throughout the year, with stronger performance towards the end of the year. This pattern can help the business plan inventory, marketing campaigns, and sales strategies more effectively.

<img width="880" height="489" alt="image" src="https://github.com/user-attachments/assets/4ed79c2e-d89f-479a-872d-e6ca90051b59" />

**Insight:**
70% Dark Bar generated the highest revenue, followed by Mixed Assortment Box and Truffle Gift Box. These products appear to be the company's strongest revenue drivers and should remain a priority for sales and marketing efforts.

<img width="692" height="474" alt="image" src="https://github.com/user-attachments/assets/efdad19e-bffd-4d5e-b5a1-201a167a0e3c" />

**Insight:** 
Australia contributed the highest revenue, while Japan recorded the lowest. This suggests stronger market performance in Australia and potential opportunities for growth in Japan.

<img width="636" height="489" alt="image" src="https://github.com/user-attachments/assets/8f667530-02f5-4958-9156-71114b1c760c" />

**Insight:**
The scatter plot and correlation analysis indicate a moderate positive relationship between marketing spend and revenue (correlation = 0.373). While revenue generally tends to increase as marketing spend increases, the relationship is not strong, and there is considerable variation in revenue across different levels of marketing spend.
This suggests that marketing spend contributes to revenue generation, but other factors such as product type, sales channel, pricing, and customer demand also influence sales performance.

## Recommendations

1. Strengthen High-Performing Products
Focus sales and marketing efforts on the highest-performing products to maximise revenue while identifying opportunities to improve lower-performing product lines.

2. Expand High-Performing Markets
Increase investment in countries with the strongest sales performance while exploring strategies to grow revenue in underperforming markets.

3. Optimise Sales Channels
Build on the success of the retail channel and develop targeted initiatives to improve the performance of the wholesale and online channels.

4. Enhance Sales Performance
Recognise top-performing sales representatives and share their best practices to improve the performance of the wider sales team.

5. Optimise Marketing Investment
Allocate marketing budgets strategically by prioritising campaigns that demonstrate the greatest impact on revenue generation.

## Conclusion

Analysis of two years of chocolate sales data (2022–2023) revealed key insights into the company's revenue, products, markets and sales performance. The business generated **$101.75 million** in total revenue, with sales remaining relatively stable throughout the analysis period and peaking in **December**, indicating seasonal demand. Product analysis showed that a small number of products contributed a significant share of total revenue, while market analysis identified the company's strongest-performing countries and confirmed that the **Retail** sales channel generated the highest revenue, followed by **Wholesale** and **Online**. Sales performance analysis also identified the top-performing sales representatives and found a **moderate positive relationship** between marketing expenditure and revenue, suggesting that marketing investment contributes to sales growth alongside other business factors.

The findings highlight opportunities to increase revenue by strengthening high-performing products, expanding successful markets, optimising sales channels and allocating marketing resources more effectively. By combining Python for data preparation and analysis with Power BI for interactive reporting, the project demonstrates how data analytics can transform raw sales data into actionable business insights that support informed strategic and operational decision-making.

## Github Link
https://github.com/gordon-moenga/Chocolate-Sales-Analysis
