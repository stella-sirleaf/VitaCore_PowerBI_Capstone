Project Overview

This project analyzes VitaCore sales data to understand product performance, revenue trends, profit performance, customer ratings, sales channels, and product returns. The goal of the project was to clean and transform raw sales data, build a structured data model, and create a dashboard that supports business decision making.

Tools Used

Microsoft Excel
Power Query
Power BI
GitHub
PowerPoint

Data Cleaning Process

The original dataset contained missing values, duplicate dimension values, date issues, and inconsistent location information. I cleaned and transformed the data using Power Query before creating the final analysis-ready dataset.

Some of the cleaning steps included:

Removed invalid date rows
Replaced blank city values with Unknown
Created Month ID for monthly analysis
Created location keys using Country, City, and Region
Created separate dimension tables for product, customer rating, sales representative, sales channel, month, and location
Removed duplicates from dimension tables
Prepared the data for a star schema model

Data Model

The cleaned dataset was structured into a fact table and multiple dimension tables. This helped create a cleaner and more organized model for analysis.

The model included:

Fact Sales
Product Dimension
Customer Rating Dimension
Sales Representative Dimension
Sales Channel Dimension
Month Dimension
Location Dimension

Key Measures Created

Total Revenue
Total Profit
Units Sold
Units Returned
Average Customer Rating
Return Rate
Profit Margin

Dashboard Focus Areas

The dashboard was designed to answer business questions such as:

Which products generated the highest revenue?
Which products generated the highest profit?
Which products had the highest return volume?
Which sales channels had the most returns?
Which regions contributed most to product returns?
What is the overall profit margin and return rate?

Key Insights

The analysis helped identify top performing products, products with high return rates, and sales channels or regions that may require further business attention. These insights can support better product strategy, sales planning, and customer experience improvement.

Project Files

This repository includes the original dataset, cleaned dataset, and presentation file for the VitaCore Sales Performance Dashboard project.

The dashboard design, analysis process, and business insights are presented in the PowerPoint file. Data cleaning and transformation were completed in Power Query using Power BI, including the creation of a star schema model with fact and dimension tables.
