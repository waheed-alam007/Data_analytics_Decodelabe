# Data Analytics Project 1 – Data Cleaning & Preparation
## Overview
This project focuses on cleaning and preparing a raw e-commerce dataset for analysis by applying industry-standard data preprocessing techniques.

## Objective
To improve data quality by:
* Handling missing values
* Removing duplicates
* Correcting inconsistent data formats
* Validating final dataset integrity
  
## Dataset Details
* Rows: 1200
* Columns: 14
* Dataset Type: E-commerce Orders Data

## Tasks Performed
* Identified missing/null values in dataset
* Replaced missing CouponCode values with "No Coupon"
* Checked and removed duplicate rows
* Validated uniqueness of OrderID values
* Standardized Date format to YYYY-MM-DD
* Removed unnecessary whitespace from text columns
* Performed final validation checks

## Final Validation Results
* Missing Values: 0
* Duplicate Rows: 0
* Duplicate Order IDs: 0

## Tools & Technologies
* Python
* Pandas
* Google Colab
* Excel
## Project Outcome
Generated a fully cleaned and analysis-ready dataset suitable for downstream analytics and reporting.
## Data Analytics Project 2 – Exploratory Data Analysis (EDA)
## Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a cleaned e-commerce dataset to uncover patterns, trends, and insights for better decision-making.

Objective Analyze dataset using statistical techniques Identify trends, patterns, and distributions Detect outliers and correlations Generate meaningful business insights Dataset Details Rows: 1200 Columns: 14 Dataset Type: E-commerce Orders Data Analysis Performed Basic statistical analysis (mean, median, count) Sales trend analysis over time Product performance analysis Payment method distribution analysis Referral source performance analysis Outlier detection using IQR method Correlation analysis between numerical features Visualizations Line Chart → Sales Trend Bar Charts → Product performance, Payment methods, Referral sources Histogram → Quantity distribution Boxplot → Outlier detection Heatmap → Correlation analysis Key Insights Strong positive correlation between UnitPrice and TotalPrice (0.71) Moderate correlation between Quantity and TotalPrice (0.61) Peak sales observed on specific dates Instagram generates higher revenue among referral sources No significant outliers in Quantity Tools & Technologies Python Pandas Matplotlib Google Colab Outcome

Successfully transformed raw data into actionable insights using EDA techniques, demonstrating analytical thinking and data-driven decision-making.

# Data Analytics Project 3 – SQL Data Analysis
## Overview

This project focuses on extracting insights from an e-commerce dataset using SQL queries. It demonstrates the ability to filter, sort, group, and aggregate data to generate business insights.
## Objective

* Use SQL to analyze dataset
* Apply filtering, grouping, and sorting
* Perform aggregations (COUNT, SUM, AVG)
* Generate meaningful insights

## Dataset

* Rows: 1200
* Type: E-commerce Orders Dataset

## SQL Queries Used

* SELECT → Retrieve data
* WHERE → Filter high-value orders
* ORDER BY → Sort data
* GROUP BY → Aggregate data

## Aggregations Performed

* COUNT → Total orders
* SUM → Total revenue
* AVG → Average order value

## Key Insights

* 512 high-value orders identified
* Maximum order value: 3456.40
* Chair and Printer generate highest revenue
* Online payment method is most used
* Facebook has highest average order value
## Tools & Technologies
* SQL (SQLite)
* Python
* Pandas
* Google Colab

## Outcome

Successfully used SQL queries to extract actionable insights from raw data, demonstrating strong data querying and analytical skills.
## Data Analytics Project 4
## Overview

This project focuses on transforming raw e-commerce data into meaningful insights using data visualization techniques. The goal is not just to create charts, but to tell a clear data-driven story that supports business decision-making.

## Objectives
Analyze sales performance across different products
Identify trends over time
Understand customer payment preferences
Evaluate order status distribution
Discover relationships between key variables
 Tools & Technologies
Python
Pandas
Matplotlib
Seaborn
Google Colab
 Dataset

The dataset contains cleaned e-commerce transaction data, including:

## Product details
Sales and profit information
Order status
Payment methods
Transaction dates
Key Analysis Performed
1. Product Sales Analysis

A bar chart was used to identify top-performing products based on total revenue.

2. Sales Trend Over Time

A line chart highlighted how sales changed over different years, helping to identify growth patterns.

3. Payment Method Insights

Bar charts were used to understand customer preferences for different payment methods.

4. Order Status Distribution

Analysis of order status helped identify delivery success rates and potential operational issues.

5. Relationship Analysis

A scatter plot showed the relationship between quantity and total price, confirming expected business behavior.

## Key Insights
Certain products contribute significantly more to total revenue.
Sales show a noticeable trend over time, indicating business growth opportunities.
Customers prefer specific payment methods, which businesses should prioritize.
Order status analysis reveals areas for operational improvement.
A strong positive relationship exists between quantity and total price.
## Conclusion
This project demonstrates how effective data visualization can transform raw data into actionable insights. It highlights the importance of choosing the right charts and focusing on storytelling to support better business decisions.


## Author
Waheed Alam
