# Customer_Behavior_Analysis

🛍️ Customer Shopping Behavior Analysis

An end-to-end Data Analytics Project that analyzes customer shopping behavior using Python, MySQL, and Power BI. The project focuses on cleaning and preprocessing customer purchase data, performing SQL-based business analysis, and building an interactive dashboard to generate actionable business insights.

📌 Project Overview

The objective of this project is to understand customer purchasing patterns, product performance, subscription behavior, and revenue trends. By integrating Python, MySQL, and Power BI, the project demonstrates the complete data analytics workflow—from raw data to interactive business reporting.

🎯 Objectives
Clean and preprocess customer shopping data using Python.
Store the cleaned dataset in MySQL.
Perform business analysis using SQL queries.
Build an interactive Power BI dashboard.
Generate insights to support business decision-making.
🛠️ Technologies Used
Python
Pandas
SQLAlchemy
PyMySQL
MySQL
Power BI
📂 Dataset Information

The dataset contains approximately 3,900 customer records with information such as:

Customer ID
Age
Gender
Category
Item Purchased
Purchase Amount
Review Rating
Subscription Status
Previous Purchases
Shipping Type
Discount Applied
Payment Method
Season
Location
🔄 Project Workflow
Customer Shopping Dataset (CSV)
            │
            ▼
Python (Data Cleaning & Preprocessing)
            │
            ▼
MySQL (Database & SQL Analysis)
            │
            ▼
Power BI (Interactive Dashboard)
🐍 Data Preprocessing (Python)

The following preprocessing steps were performed:

Imported dataset using Pandas
Checked data types and missing values
Removed duplicate records
Renamed columns using snake_case
Filled missing review ratings using category-wise median
Created Age Group column
Created Purchase Frequency Days column
Removed unnecessary columns
Loaded cleaned data into MySQL
🗄️ SQL Business Analysis

The following business questions were solved using MySQL:

Calculate total revenue.
Find the average purchase amount.
Identify the Top 5 highest-rated products.
Compare average purchase amount by shipping type.
Compare spending between subscribed and non-subscribed customers.
Find the Top 5 products with the highest percentage of discounted purchases.
Segment customers into New, Returning, and Loyal customers.
Find the Top 3 most purchased products in each category.
Analyze whether repeat buyers are more likely to subscribe.
Calculate revenue contribution by age group.
📊 Power BI Dashboard

The dashboard includes:

KPI Cards
Total Customers
Total Revenue
Total Orders
Average Review Rating
Interactive Filters
Subscription Status
Gender
Age Group
Category
Visualizations
Revenue by Category
Revenue by Season
Sales by Gender
Subscription Distribution
Shipping Type Distribution
Revenue by State
Sales Table
Reset Filters Button
📈 Key Insights
Clothing category generated the highest revenue.
Most customers are non-subscribers.
Subscribers spend more on average than non-subscribers.
Young Adult customers contribute significantly to total revenue.
Summer season recorded the highest sales.
Average customer review rating is approximately 3.8.
💡 Business Recommendations
Increase customer subscriptions through loyalty programs.
Promote top-selling and highly rated products.
Offer personalized discounts to repeat customers.
Improve low-rated products using customer feedback.
Use seasonal trends to plan marketing campaigns.
Monitor business performance using the Power BI dashboard.

🚀 Skills Demonstrated
Data Cleaning,
Data Preprocessing,
Exploratory Data Analysis (EDA),
SQL Query Writing,
Database Management,
Power BI Dashboard Development,
Data Visualization,
Business Intelligence,
Data Analytics
