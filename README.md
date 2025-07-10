**E-Commerce Data Analysis Project**

This project explores and analyzes an E-Commerce transactional dataset using Python. It involves data cleaning, exploratory data analysis (EDA), visualization, and key customer and product insights.

**Dataset Overview**
File Name: Data.csv

Rows: 112,803

Columns: 8

Key Columns:

InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

**Data Cleaning**
//
Removed missing CustomerID and Description values.

Removed entries with non-positive Quantity or UnitPrice.

Final cleaned dataset: 72,889 rows

Key Analysis & Insights
Sales Analysis
Total Net Revenue: £1,584,824.50

Total Items Sold: 995,093

Monthly Revenue Trend: Identified seasonal peaks and drops

30-Day Rolling Average: Smoother trend to analyze business performance

**Weekday Analysis**
//
Found which weekdays have the highest average item volume per invoice.

Product Analysis
Top 10 Products by Quantity Sold

Top 10 Products by Revenue

Distribution of order quantity and unit price

**Customer Behavior**

Unique Customers: 1,790

Repeat Purchase Rate: 39.27%

Average Order Value (AOV): £955.81

Revenue by Country: Top 10 countries visualized

**Visualizations**

Key plots created using matplotlib:

Monthly revenue trends

Weekday sales distribution

Top product charts

Country-wise revenue

Quantity and price distributions

Rolling average revenue trends

**Tools Used**

Python

Pandas

NumPy

Matplotlib

Jupyter Notebook / Google Colab# Python
