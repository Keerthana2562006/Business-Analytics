📊 SALES PERFORMANCE DASHBOARD

📌 Project Overview

This project presents an interactive Power BI Sales Performance Dashboard developed using the Superstore Sales Dataset.

The main objective is to help management quickly understand sales performance across products, categories, and regions and identify important business patterns.

🎯 Objectives

📈 Analyze overall sales performance                                                                                                    
💰 Evaluate profitability                                                                                                               
📦 Compare sales across product categories                                                                                              
🏆 Identify top-performing products                                                                                                     
🌎 Analyze regional and state-level sales performance                                                                                   
📅 Understand monthly sales trends                                                                                                      
🔍 Identify important business patterns                                                                                                 
🎛️ Provide interactive filtering                                                                                                        
💡 Support data-driven decision making                                                                                                   
                                                                                                                                        
📂 Dataset

The project uses the Superstore Sales Dataset.

The dataset contains 9,994 records and 19 columns.

Important fields include:

📅 Order Date                                                                                                                          
🚚 Ship Date                                                                                                                            
👤 Customer ID                                                                                                                          
👥 Segment                                                                                                                             
🌎 Country                                                                                                                              
🗺️ State                                                                                
📍 City                                            
🌍 Region                                    
📦 Category                                            
📂 Sub-Category                                      
🏷️ Product Name                                  
💰 Sales                                
💵 Profit                              
📊 Quantity                              
🏷️ Discount                                
                                        
🧹 Data Preparation                      

The data was prepared using Power Query.

Main preparation steps:

✅ Checked and corrected data types                                
✅ Converted Order Date and Ship Date to Date                          
✅ Set Sales and Profit as decimal numbers                
✅ Formatted Discount as a percentage                              
✅ Checked duplicate records                              
✅ Verified geographical fields                        
✅ Created Month Name                                    
✅ Created Month No for correct month sorting                              
                                    
🧮 DAX Measures                          
                                        
💰 Total Sales                          

Total Sales = SUM('Superstore'[Sales])


💵 Total Profit

Total Profit = SUM('Superstore'[Profit])


🧾 Total Orders

Total Orders = DISTINCTCOUNT('Superstore'[Order ID])


📦 Units Sold

Units Sold = SUM('Superstore'[Quantity])


📊 Profit Margin

Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)


👥 Total Customers

Total Customers = DISTINCTCOUNT('Superstore'[Customer ID])


📊 Dashboard Visualizations

The dashboard contains the following visuals:

💳 KPI Cards

💰 Total Sales                          
💵 Total Profit                                        
📊 Profit Margin                                    
🧾 Total Orders                                      
📦 Units Sold                                      
👥 Total Customers                                

📈 Monthly Sales Trend                            

A line chart is used to analyze sales performance across different months.

🗺️ State-Level Sales Performance                              

A map is used to visualize sales distribution across different states and identify geographical sales patterns.

📦 Sales by Category                          

A bar chart is used to compare sales across:

💻 Technology                                    
🪑 Furniture                                    
📚 Office Supplies                              

🏆 Top 5 Products by Sales                          

A bar chart identifies the five products with the highest sales.

💹 Profitability by Category

A chart compares the profit generated by different product categories.

🎛️ Interactive Slicers

The dashboard includes interactive filters for:

🌎 Region                          
📦 Category                      
👥 Segment                            

These slicers allow users to dynamically filter the dashboard and perform focused analysis.

🔍 Key Business Insights

💰 Overall Performance

The business generated approximately ₹2.30 million in sales and ₹286.40 thousand in profit, with a profit margin of approximately 12.47%.

📦 Category Performance

Technology is the leading category in terms of sales and profitability.

🌎 Regional Performance

The West region contributes the highest sales among the four regions.

🏆 Product Performance

The Canon imageCLASS 2200 Advanced Copier is among the top-performing products by sales.

📈 Sales Trend

Monthly analysis helps identify changes and fluctuations in sales performance throughout the year.

💡 Profitability Pattern

High sales do not always result in proportionally high profit. Comparing both sales and profit helps identify categories that may require further investigation.

💼 Business Value

The dashboard helps management:

🎯 Identify high-performing products                          
📦 Understand category performance                                          
🌎 Evaluate regional performance                          
📈 Monitor sales trends                                
💰 Analyze profitability
⚠️ Identify areas requiring improvement                              
📊 Support data-driven decision making                                

🛠️ Tools & Technologies

📊 Power BI Desktop                          
🔄 Power Query                                      
🧮 DAX                              
📁 CSV Dataset                                
🐙 GitHub                                  

🎨 Dashboard Design

The dashboard follows a clean and professional management-oriented design.

Design features:

🎨 Consistent color scheme    
📊 Clear KPI presentation  
📐 Proper alignment and spacing    
🔤 Readable typography  
🎛️ Interactive slicers  
📈 Simple and meaningful visualizations  
🚫 Minimal visual clutter  

The dashboard is designed so that management can understand the major business patterns within 5–10 seconds.

📸 Dashboard Preview

Add your Power BI dashboard screenshot here.

![Sales Performance Dashboard](dashboard.png)

📁 Project Structure

Sales-Performance-Dashboard/

├── README.md      
├── Sales_Performance_Dashboard.pbix    
├── Sample_Superstore.csv  
├── Sales_Performance_Report.docx  
└── dashboard.png  

✅ Project Outcome  

The final Power BI dashboard transforms raw Superstore sales data into an interactive, visually clear, and management-focused business intelligence solution.

It provides a quick overview of sales, profit, products, categories, and geographical performance while allowing users to explore the data through interactive filters.

The dashboard supports management in identifying business opportunities, understanding performance patterns, and making informed data-driven decisions.

👩‍💻 Author

Keerthana R

Bachelor of Computer Applications  
Business Analytics – Semester V  


