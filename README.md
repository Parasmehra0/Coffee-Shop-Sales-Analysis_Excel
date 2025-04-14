# Coffee-Shop-Sales-Analysis_Excel

☕ Coffee Shop Sales Analysis 📊

This project is an Excel-based analytical dashboard built using raw transactional data from a coffee shop. It transforms basic sales data into actionable insights using Excel functions, PivotTables, slicers, and visualizations. This repository includes both the original data and the finalized interactive report.

📂 Files Included 
Base file_Coffee Shop Sales.xlsx➔ Raw transactional data with product details, pricing, store information, and timestamps.
Final report_Coffee Shop Sales.xlsx➔ Completed analytical dashboard using PivotTables, charts, and slicers for interactivity.

🔹 Features Implemented
✅ Columns Created:
Month ➔ Extracted using: =TEXT([@Date], "mmmm")
Weekday ➔ Extracted using: =TEXT([@Date], "dddd")
Hour ➔ Derived from time using: =HOUR([@Time])
Total Amount ➔ Calculated using: =Quantity * Unit Price
Category ➔ Assigned based on product logic using IF/VLOOKUP

✅ Pivot Tables:
Total Revenue by Month & Category
Sales Volume by Hour of Day
Revenue by Payment Type
Product Performance (Top N)
Store-wise Comparison

✅ Pivot Charts:
Line Chart: Monthly Revenue Trend
Column Chart: Hourly Sales
Pie Chart: Payment Type Distribution
Bar Chart: Top Selling Products


📊 Key Business Insights
Beverages dominate overall revenue, with Coffee and Espresso being top performers.
Sales peak during morning (8-11 AM) and late afternoon (4-6 PM).
Saturday and Friday consistently generate higher traffic and sales.
Cash payments are still preferred, although digital payments are growing.
Merchandise has lower sales frequency but high average value per transaction.

🛠️ Tools & Techniques
Microsoft Excel
Data Cleaning
PivotTables & PivotCharts
Slicers for interactivity
Cell Formatting & Conditional Highlighting
formulas

📆 Use Cases
Retail Sales Analysis
Store Performance Dashboards
Customer Trend Monitoring
Operational Planning
