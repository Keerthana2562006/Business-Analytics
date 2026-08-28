📊 Retail Sales Analysis using MySQL & Power BI
📌 Project Overview

This project demonstrates how business datasets can be imported into MySQL and connected to Microsoft Power BI for data analysis and visualization.

The project uses three main tables:                                                                                                     

Sales                                                                                                                                   
Products                                                                                                                                
Customers                                                                                                                               

The data is prepared using Power Query, relationships are created between the tables, and DAX measures are used to calculate key business metrics.

🎯 Problem Statement

A retail company stores its business data across multiple sources. Management requires a centralized reporting system to analyze sales and customer performance.

The objective of this project is to:

Import business datasets into MySQL                                                                                                     
Connect MySQL with Power BI                                                                                                             
Create relationships between Sales, Products, and Customers                                                                          
Prepare and transform the data                                                                                                          
Create an interactive Power BI dashboard                                                                                                
Analyze sales performance using charts, KPI cards, and slicers                                                                               
🗂️ Dataset

The project uses three datasets:

1. Customers

Contains customer-related information such as:

CustomerID
FirstName
LastName
Country
City
Customer information
2. Products

Contains product-related information such as:

ProductID
Product Name
Category
Brand
Price
Availability
EAN
3. Sales

Contains transaction information such as:

OrderID
OrderDate
CustomerID
ProductID
Quantity
UnitPrice
SalesAmount
🛠️ Tools & Technologies
Tool	Purpose
MySQL	Database storage
Power BI Desktop	Data visualization
Power Query	Data cleaning and transformation
DAX	Measures and calculations
CSV	Dataset source
GitHub	Project documentation
🔄 Project Workflow
CSV Datasets
     ↓
   MySQL
     ↓
Sales ───── Products
   │
   │
Customers
     ↓
Power BI
     ↓
Power Query
     ↓
Data Modeling
     ↓
DAX Measures
     ↓
Interactive Dashboard

The Sales, Products, and Customers tables are connected using appropriate key fields and one-to-many relationships.

🧹 Data Preparation

The following data preparation steps were performed:

Removed duplicate records
Handled missing values
Renamed columns where required
Converted columns to appropriate data types
Created relationships between tables
📐 DAX Measures

Basic DAX measures were created for:

Total Sales
Total Orders
Total Customers

These measures were used in KPI cards and visualizations.

Example:

Total Sales = SUM(Sales[SalesAmount])
Total Orders = DISTINCTCOUNT(Sales[OrderID])
Total Customers = DISTINCTCOUNT(Customers[CustomerID])
📊 Dashboard

The Power BI dashboard includes:

KPI Cards
💰 Total Sales
🧾 Total Orders
👥 Total Customers
Visualizations
📦 Sales by Category
🌍 Sales by Country
📈 Monthly Sales Trend
👤 Sales by Customer
Slicers
Country
Category
Order Date

A consistent grey colour theme was applied to the dashboard.

📈 Business Insights

The dashboard provides a centralized view of:

Overall sales performance
Customer-wise sales
Category-wise sales
Country-wise sales
Monthly sales trends
Key business KPIs

Interactive slicers allow users to filter the analysis by Country, Category, and Order Date.

🎓 Learning Outcomes

Through this project, I learned:

How to import CSV datasets into MySQL.                                                                                                  
How to connect MySQL with Power BI.                                                                                                    
How to work with multiple tables.                                                                                                       
How to create relationships in Power BI.                                                                                                
How to use Power Query for data preparation.                                                                                            
How to create DAX measures and calculated columns.                                                                                      
How to create KPI cards, charts, and slicers.                                                                                           
How to design an interactive Power BI dashboard.                                                                                        
How to present business data using meaningful visualizations.                                                                                                                                                      
👩‍💻 Author

Keerthana R

Bachelor of Computer Applications
Business Analytics – Semester V
