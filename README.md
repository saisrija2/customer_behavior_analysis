📊 Customer Shopping Behavior Analysis

📌 Overview

This project analyzes customer shopping behavior using an end-to-end data analytics workflow.
The objective is to understand purchase patterns, customer demographics, spending behavior, and promotional impact to support data-driven business decisions.

The project demonstrates hands-on experience with Python, SQL, Power BI, and business reporting.

📂 Dataset

Name: Customer Shopping Behavior Dataset

Format: Excel / CSV

Records: 3,900 rows

Columns: 18

Type: Structured customer transaction data

Key Columns

Customer ID, Age, Gender, Location

Item Purchased, Category, Size, Color, Season

Purchase Amount (USD), Review Rating

Subscription Status, Shipping Type

Discount Applied, Promo Code Used

Payment Method, Frequency of Purchases

Previous Purchases

🛠 Tools & Technologies

Python

Libraries: pandas, numpy, matplotlib, seaborn

SQL

PostgreSQL / MySQL / SQL Server

Power BI

Data modeling and interactive dashboards

Gamma

Business presentation (PPT)

Excel

Initial validation and sanity checks

🔍 Project Workflow
1️⃣ Data Loading

Loaded dataset using pandas

Verified schema, data types, and structure

2️⃣ Exploratory Data Analysis (EDA)

Analyzed:

Customer demographics (age, gender, location)

Spending patterns and purchase frequency

Category and season-based trends

Identified outliers and data inconsistencies

Visualized distributions and relationships

3️⃣ Data Cleaning

Standardized column names

Checked and handled missing values

Converted data types where required

Removed duplicates 

4️⃣ SQL Analysis

Loaded cleaned data into SQL databases

Answered business questions such as:

Which categories generate the highest revenue?

Do discounts and promo codes increase purchase frequency?

Which customer segments spend more?

Used:

GROUP BY, JOIN, CTE

Window functions for ranking and trend analysis

5️⃣ Power BI Dashboard

Built interactive dashboards featuring:

Total Revenue & Average Order Value

Category-wise and season-wise sales

Customer segmentation by age, gender, and location

Impact of discounts and subscriptions

Enabled filters for deep-dive analysis

6️⃣ Reporting & Presentation

Created a structured analysis report

Designed a stakeholder-ready PPT using Gamma

Focused on insights, not just charts 
📈 Dashboard Highlights

Revenue by Category & Season

Customer Demographics Overview

Discount vs Non-Discount Purchase Behavior

Subscription vs Non-Subscription Analysis

Purchase Frequency Trends
<img width="1222" height="674" alt="Screenshot 2026-02-09 182937" src="https://github.com/user-attachments/assets/66ec1f8b-e6e5-4e71-9525-00d02342e870" />



▶️ How to Run the Project
Python Environment
pip install pandas numpy matplotlib seaborn

python eda_analysis.py

SQL

Import cleaned dataset into PostgreSQL / MySQL / SQL Server

Execute queries from sql_analysis.sql

Power BI

Open the .pbix file

Refresh data sources if needed

🎯 Skills Demonstrated

Data Cleaning & EDA

SQL-Based Business Analysis

Data Modeling & Visualization

Dashboard Design


