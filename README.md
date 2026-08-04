# Restaurant-Sales-&-Performance-Analysis-Dashboard
## Overview
A fast-growing restaurant chain, operating multiple brands across major cities, lacks a centralized reporting system to monitor sales performance, customer trends, operational efficiency, and profitability. This project builds an interactive dashboard to track sales, profitability, customer behavior, and operations.

## Tools
• Power BI for data modeling, analysis, and visualization

• Power Query to clean, transform, and standardize raw data

• DAX to create core financial and performance measures.

## Overview of the Dataset
The dataset contained 80,000 transactional records collected from all branches between 1 January 2022 and 31 December 2025. The data includes information about:

• Restaurant branches

• Customers

• Products

• Employees

• Suppliers

• Promotions

• Daily sales transactions

## Data Cleaning
The dataset required cleaning before analysis. Power Query was used to clean, standardize, and prepare the data for reliable reporting.
The following steps were implemented to clean the data:

• Removed duplicate records from columns where deemed necessary to ensure data accuracy

• Standardized column names, data types, and date formats across all tables

• Replaced Blank Values with NA or 0 where  appropriate

• Corrected inconsistent text across the columns

• Standardized inconsistent categorical values

• Removed extra whitespace and standardized text casing (proper case) across columns for naming consistency

• Created a conditional column to derive Subcategory from Item Name, filling gaps in the product hierarchy.

## Data Modeling
After cleaning, a star schema data model was built by connecting the fact table to the dimension tables.

## Data Analysis
DAX measures were created to calculate the following metrics:

• Total Sales

• Gross Sales

• Net Sales

• Profit

• Profit Margin %

• Total Orders

• Total Customers

• Average Order Value

• Average Customer Rating

• Total Discount

• Year-to-Date Sales

• Month-to-Date Sales

• Quarter-to-Date Sales

• Previous Year Sales

• Year-over-Year Growth %

## Data Visualization
[Download the dashboard](restaurant-sales-dashboard.pbix)
