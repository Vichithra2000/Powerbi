# E-Commerce Sales Analysis – Data Transformation & Data Modeling (Power BI)
## Project Overview
This repository contains the Power BI Data Transformation and Data Modeling project focused on analyzing e-commerce sales performance. Using Power Query Editor and Power BI Desktop, raw transactional and target datasets were imported, cleaned, enriched with custom business logic, aggregated, and connected into a relational data model to support actionable business intelligence.
## Dataset Description
List of Orders.csv: Contains order-level metadata including Order ID, Order Date, CustomerName, State, and City.

Order Details.csv: Contains line-item transactional data including Order ID, Amount, Profit, Quantity, Category, and Sub-Category.

Sales target.csv: Contains monthly sales targets segmented by Category and Month of Order Date.
## Key Steps
### Import Data:
Imported List of Orders.csv, Order Details.csv, and Sales target.csv into Power BI Desktop and launched the Power Query Editor 
### Data Transformation:
- Row Filtering: Restricted the List of Orders table to the top 500 rows (Keep Top Rows) to establish a focused working sample.

- Data Type Standardization: 
Converted Order Date to the Date data type.

  Converted Amount and Target columns to Fixed Decimal Number (Currency) to ensure financial precision.

- Text Formatting & Concatenation:

  Standardized CustomerName using Capitalize Each Word (Proper Case).

  Merged City and State into a single formatted column named Location (City, State).

