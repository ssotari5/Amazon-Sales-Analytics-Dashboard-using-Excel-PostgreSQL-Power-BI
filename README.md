Amazon Sales Analytics Dashboard

End-to-End Data Analytics Project using Excel, PostgreSQL & Power BI

📁 Dataset Source

This project uses a publicly available synthetic e-commerce dataset from Kaggle that simulates Amazon-style sales transactions.

🔗 Amazon Sales Dataset — Kaggle
https://www.kaggle.com/datasets/rohiteng/amazon-sales-dataset

The dataset contains 100,000+ records and 20 well-structured columns representing order details, customers, products, pricing, taxes, shipping cost, order status, and payment methods. It is ideal for analytics, SQL practice, and Power BI dashboard projects.

📋 Project Overview

This project demonstrates an end-to-end data analysis pipeline using:

Excel → data cleaning & preprocessing

PostgreSQL → data modeling & SQL KPI views

Power BI → interactive dashboards & business insights

The final deliverable is a 2-page Power BI dashboard that reveals sales performance, product trends, customer behavior, and operational insights.

🛠️ Tools & Technologies
Tool	Purpose
Excel	Cleaning, formatting, preprocessing dataset
PostgreSQL	Importing data, designing schema, creating KPI views
Power BI	Building interactive dashboards & visual insights
GitHub	Version control & project documentation
🧹 1. Excel — Data Cleaning

Key steps:

Removed blank rows & invalid entries

Standardized date formats, numeric fields & text formatting

Ensured product, customer, and location names were consistent

Exported clean data for SQL ingestion

File: amazon_sales_cleaned.xlsx

🗄️ 2. PostgreSQL — Data Modeling & SQL Views

After importing the cleaned dataset into PostgreSQL:

🔧 Data Modeling Steps

Added a datekey column to support a proper date dimension

Created a Date table with Year, Month, Quarter, and Day fields

Built SQL views to simplify Power BI reporting

Created one-to-many and many-to-many logical relationships using SQL structure rather than Power BI

🧾 Key SQL Views

v_customer_sales → Lifetime value & order count per customer

v_order_status → Orders grouped by status

v_product_performance → Revenue & units sold per product

v_sales_summary → Total sales, orders & units per day

All scripts are included in:
📄 sql_views_and_model.sql

📊 3. Power BI — Dashboard Development

Connected Power BI directly to the PostgreSQL server, imported SQL views, and created a clean data model.

⭐ Page 1 — Sales Overview Dashboard

Includes:

Total Sales, Total Orders, Units Sold, Total Customers (KPIs)

Monthly Sales Trend

Order Trend

Sales by State (Treemap)

Top Cities by Revenue

Order Status Breakdown

Slicers for Year, Month, Category, Country, and Payment Method

⭐ Page 2 — Product Insights Dashboard

Includes:

Revenue Trend Over Time

Profit vs Sales Scatter Plot

Top 10 Products by Revenue

Slicers for Category, Brand, Product Name, and Year

PBIX File: Amazon_Sales_Dashboard.pbix
(If file size exceeds GitHub limits, a Google Drive link is provided in this repository.)

📸 Screenshots

Located in the /screenshots folder:

sales_overview.png

product_insights.png

model_view.png

sql_code.png

📈 Key Insights

Mid-year months showed the highest sales volume

Texas and California were top-performing states

Most orders were successfully delivered, indicating strong operational efficiency

High-revenue products included Electric Kettles, Memory Cards & Board Games

Revenue displayed clear seasonal patterns

🚀 How to Reproduce

Clone or download this repository

Load amazon_sales_cleaned.xlsx into PostgreSQL

Run SQL scripts from sql_views_and_model.sql

Open the Power BI file Amazon_Sales_Dashboard.pbix

Update your PostgreSQL connection credentials

Refresh all visuals

📂 Repository Structure
Amazon-Sales-Analytics-Project
│
├── amazon_sales_cleaned.xlsx
├── sql_views_and_model.sql
├── Amazon_Sales_Dashboard.pbix
│
├── screenshots/
│   ├── sales_overview.png
│   ├── product_insights.png
│   ├── model_view.png
│   └── sql_code.png
│
└── README.md

🙋‍♂️ About This Project

Through it, I strengthened my skills in:

Data cleaning & preprocessing

SQL query writing & view creation

Data modeling & relationships

Power BI visualization & storytelling

I look forward to taking on more real-world analytics projects!

📫 Contact

If you'd like to view the SQL scripts, Power BI file, or collaborate:
LinkedIn: https://www.linkedin.com/in/siddhesh-otari/
Email: ssotari5@gmail.com
