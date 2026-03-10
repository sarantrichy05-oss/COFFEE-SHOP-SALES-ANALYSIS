# Coffee Shop Sales Analysis

An interactive Power BI dashboard analyzing coffee shop transaction data to understand revenue trends, product demand, and store performance across different locations and time periods.

---

## Table of Contents

- Project Overview
- Data Source
- Tools & Technologies
- Data Cleaning & Preparation
- Exploratory Data Analysis (EDA)
- Key Insights
- Recommendations
- How to Use

---

##  Project Overview

This project analyzes coffee shop sales data using Microsoft Power BI to understand business performance and customer purchasing behavior.

The main objective of this analysis is to identify sales trends, evaluate store performance, analyze product demand, and understand customer purchasing patterns during different times of the day. By converting raw transactional data into an interactive dashboard, the project helps support data-driven business decisions related to inventory management, marketing strategies, and operational improvements.

---

## Data Source

The dataset used in this project was obtained from **Maven Analytics Data Playground**, which provides datasets for analytics practice and learning.

**Source Link:**  
https://mavenanalytics.io/data-playground/coffee-shop-sales

**Domain:** Food & Beverage Analytics

### Key Variables

- Transaction ID
- Transaction Date
- Transaction Time
- Store Location
- Product Category
- Product Type
- Product Detail
- Transaction Quantity
- Unit Price
- Total Sales

Additional columns such as **Hour** and **Time Period** were created to analyze customer purchasing behavior throughout the day.

---

## Tools & Technologies

**Visualization Tool:** Power BI Desktop

Power BI was used for:

- Data Cleaning and Transformation (Power Query)
- Data Modeling using Star Schema
- DAX Calculations
- Interactive Dashboard Visualization

---

## Data Cleaning & Preparation

Several data preparation steps were performed before creating the dashboard.

- Removed duplicate records
- Handled missing values
- Standardized date and time formats
- Created calculated columns for revenue analysis
- Generated time-based attributes such as Hour and Time Period


A **Date Table** was also created to support time-based reporting and trend analysis.

---

## Exploratory Data Analysis (EDA)

The analysis focused on answering several important business questions:

- What is the overall sales trend over time?
- Which store location generates the highest revenue?
- Which product categories contribute the most to sales?
- At what time of day do customers make the most purchases?
- Which products generate the highest revenue?

### Dashboard Visualizations

The Power BI dashboard includes the following visualizations:

- Monthly Revenue Trend
- Revenue by Time Period
- Store Location Performance
- Category-wise Revenue Distribution
- Hourly Sales Performance
- Product Type Revenue Contribution
- Geographical Sales Distribution Map

https://github.com/sarantrichy05-oss/COFFEE-SHOP-SALES-ANALYSIS/blob/ef4ffa8e2b4debfccf0697633191de409aa907a1/DASHBOARD.pdf

---

##  Key Insights

- Revenue steadily increased from March to June, with June recording the highest sales.
- Morning hours generate the majority of revenue, contributing more than half of total daily sales.
- Coffee is the primary revenue-generating category, followed by Tea and Bakery products.
- Barista Espresso and Brewed Chai Tea are among the highest-performing products.
- Most transactions consist of a single item, indicating a high-frequency "grab-and-go" purchasing pattern.

---

##  Recommendations

- Increase staffing and inventory during peak morning hours to handle high customer demand.
- Promote top-performing beverages such as espresso and brewed coffee through targeted marketing.
- Introduce combo offers that bundle coffee and bakery products to increase transaction value.
- Monitor store-level performance and implement location-specific promotional strategies.
- Maintain adequate stock levels for high-demand products to prevent shortages during peak hours.

---

## How to Use

1. Download the **Power BI (.pbix) file** from this repository.
2. Open the file using **Microsoft Power BI Desktop**.
3. Explore the interactive dashboard and visualizations.
4. Use filters and slicers to analyze data by:
   - Store Location
   - Product Category
   - Time Period
   - Date

### Requirements

- Microsoft Power BI Desktop
