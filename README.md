📊 Swiggy Data Analysis Project

📌 Project Overview

This project focuses on analyzing Swiggy food delivery data to extract meaningful business insights using Excel, SQL, a The goal is to understand customer behavior, identify sales trends, and build interactive visualizations that support data-driven decision-making.
The dataset includes order-level information such as customer details, product categories, pricing, quantity, tax, total revenue, payment methods, and ratings. By transforming and analyzing this data, the project demonstrates how raw data can be converted into actionable insights.


---
🎯 Objectives
To clean and preprocess raw transactional data for analysis
To analyze sales performance across different cities and categories
To identify trends in customer purchasing behavior
To evaluate revenue distribution and peak sales periods
To design an interactive dashboard for business reporting

🛠️ Tools & Technologies Used
📊 Microsoft Excel
Data cleaning (handling missing values, formatting)
Pivot tables for summarization
Dashboard creation with charts and slicers

- excel sheet of analysis
- <img width="1080" height="700" alt="31823" src="https://github.com/user-attachments/assets/c1434d57-70dc-4ca5-bb08-541b5a09ddc1" />


- SQL (Data Querying)
- 🗄️ SQL (Microsoft SQL Server)
Data querying and aggregation
Grouping and filtering large datasets
Conditional aggregation using CASE WHEN
Monthly and region-wise sales analysis
- <img width="1536" height="1024" alt="31879" src="https://github.com/user-attachments/assets/6502c054-df2a-47f4-933d-5bca97a5c3ab" />

---

📂 Dataset

- Swiggy_Data.csv
- Swiggy_Data.xlsx
- 📂 Dataset Description
The dataset contains structured transactional records with the following key attributes:
Invoice ID – Unique identifier for each transaction
Branch / City – Location of the order
Customer Type – Member or Normal
Gender – Customer demographic
Product Line – Category of product purchased
Unit Price & Quantity – Pricing details
Tax & Total – Revenue calculations
Date & Time – Timestamp of transaction
Payment Method – Cash, Credit Card, E-wallet
COGS & Gross Income – Cost and profit indicators
Rating – Customer satisfaction score
📊 Data Processing Steps
Data Cleaning
Removed inconsistencies and formatting issues
Standardized column names and data types
Verified null/missing values
Data Transformation
Extracted month from date for trend analysis
Categorized regions based on city
Created calculated fields (Total Sales, Profit)
Data Analysis
Aggregated monthly sales using SQL
Compared regional performance
Identified top-selling product categories
🗄️ SQL Analysis Explanation
SQL was used to perform efficient aggregation and filtering of data. One key query calculates monthly sales by region using conditional aggregation:
DATENAME(MONTH, Date) extracts the month name
SUM(CASE WHEN ...) calculates region-wise totals
GROUP BY ensures monthly aggregation
ORDER BY maintains chronological order
This approach allows comparison of different regions in a single query result.

---

📊 Key Features

- Data Cleaning & Transformation
- Pivot Table Analysis
- Interactive Dashboard
- Sales & Order Insights
- pivot table analysis
- 
<img width="1080" height="420" alt="31846" src="https://github.com/user-attachments/assets/854bfd20-004b-41d2-844e-27baf46db36f" />
---
📈 Key Insights
Certain regions consistently generate higher revenue compared to others
Sales show noticeable variation across months, indicating seasonal trends
Customer purchasing behavior differs based on location and category
Digital payment methods are widely preferred
High-rated transactions often correlate with higher-value orders
💼 Business Impact
This analysis can help businesses:
Optimize inventory and supply chain decisions
Improve marketing strategies based on customer trends
Identify high-performing regions and products
Enhance customer experience using feedback data
🚀 How to Use This Project
Download or clone the repository
Open the dataset in Excel or import into SQL Server
Run SQL queries for analysis
Explore the Excel dashboard for visual insights
🔮 Future Enhancements
Build a Power BI interactive dashboard
Implement predictive analytics using Machine Learning
Automate data pipeline using ETL tools
Deploy insights using a web dashboard
-dashboard analysis 




📈 Insights

- Identified top-selling categories
- Analyzed customer ordering patterns
- Found peak order timings
- dashboard insights
- <img width="1080" height="927" alt="31892" src="https://github.com/user-attachments/assets/87352bd6-2af1-426b-8231-fa52692d4cba" />




---





