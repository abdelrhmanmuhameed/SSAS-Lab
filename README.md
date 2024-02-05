# SSAS-Lab
<h1>Hey Data Enthusiasts! 👩‍💻👨‍💻</h1>

We are thrilled to share our latest SSAS (SQL Server Analysis Services) lab project now available on GitHub - "DataWarehousing with Internet Sales." This project provides an immersive learning experience in building cubes and exploring multidimensional data in Microsoft's SQL Server environment.

<h1>🔍 Project Highlights:</h1>

1. Product Cube:

Objective: Analyze Product Quantity over the Years.
Dimensions:
Product Dimension (Product ID, Product Name)
Time Dimension (Calendar Year)
Measure:
Fact Sales (Quantity)
2. Prod_Cust Cube:

Objective: Understand the Relationship between Product, Customer, and Time.

Dimensions:
Product Dimension (Product ID, Product Name, Product Category)
Customer Dimension (Customer ID, Customer Name, Customer Address)
Time Dimension (Calendar Year, Calendar Quarter)
Measures:
Fact Sales (Quantity, Total Price)
Calculated Measure: "Sales Unit Price" (Expression: [Qty Total Price] / [Qty])
KPI:
"Qty KPI" indicating Sales Quantity should be at least 1000 units with Faces status indicator.
Localization:
Arabic translation for dimensions and measures.
Analysis:

Pivot Table and Pivot Chart illustrating the variance between "Qty KPI" and actual Quantity using Microsoft Excel.
3. Sales Cube:

Objective: Showcase All Dimensions in SalesDW with key Measures.
Measures:
Customer Count, Product Count, Salesman Count, Channel Count, Quantity, Total Price, Fact Table Count (Number of Orders)
Perspective:
"Channel Product Perspective" displaying Customer Name, Channel Location, Quantity Measure, and Total Price for each Quantity.
4. Excel Integration:

Leverage Microsoft Excel to create Pivot Tables and Pivot Charts for in-depth analysis using the data from "Product Cube" and "Sales Cube."
🛠️ Get Started:

Let's dive into the world of data analysis and unleash the power of SQL Server Analysis Services! 📊🚀 Feel free to contribute, provide feedback, or raise issues on our GitHub repository.
