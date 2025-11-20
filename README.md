🛍️ Customer Shopping Behavior Analysis

A Data Analysis Project using Python, SQL, and Power BI

📌 Project Overview

This project analyzes customer shopping behavior using 3,900+ transactional records to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior. The goal is to support better business decisions using end-to-end data processing — from cleaning to visualization.


Customer Shopping Behavior Anal…

📂 Dataset Summary

Rows: 3,900

Columns: 18

Key Features:

Customer demographics — Age, Gender, Location, Subscription Status

Purchase details — Item, Category, Amount, Season, Size, Color

Shopping behavior — Discounts, Promo Codes, Previous Purchases, Frequency, Review Rating, Shipping Type

Missing Data: 37 values in the Review Rating column (handled during cleaning)


Customer Shopping Behavior Anal…

🧹 Data Cleaning & Transformation (Python)

Performed using Pandas, NumPy, and PostgreSQL integration.
Key steps:

Loaded and explored the dataset (df.info(), df.describe()) 

Customer Shopping Behavior Anal…

Imputed missing ratings using median per category

Renamed columns to snake_case for consistency

Created new engineered features:

age_group (binned ages)

purchase_frequency_days

Removed redundant columns (promo_code_used) after consistency checks

Loaded the cleaned DataFrame into a PostgreSQL database


Customer Shopping Behavior Anal…

🧠 SQL Analysis – Business Insights

Using PostgreSQL, multiple real-world business questions were answered:

Revenue breakdown by gender

High-spending customers who still used discounts

Top 5 products by average rating

Purchase amount comparison by shipping type

Subscriber vs non-subscriber spending

Discount-dependent products

Customer segmentation: New / Returning / Loyal

Top 3 products in each category

Subscription likelihood for repeat buyers

Revenue contribution by age group


Customer Shopping Behavior Anal…

📊 Power BI Dashboard

An interactive dashboard was created to present insights visually, including:

Revenue trends

Customer segmentation

Product performance

Subscription insights

Demographic breakdowns


Customer Shopping Behavior Anal…

💡 Business Recommendations

Based on the analysis, the following strategies were suggested:

Promote subscription benefits

Strengthen loyalty programs

Optimize discount policies

Highlight high-rated and best-selling products

Target marketing to profitable age groups and express shipping users


Customer Shopping Behavior Anal…

🛠️ Tech Stack
Skill	Tools Used
Data Cleaning & Preparation	Python, Pandas, NumPy
Feature Engineering	Python
Database & Querying	PostgreSQL, SQL
Business Insights	SQL
Visualization	Power BI
Version Control	GitHub
📁 Repository Structure (Suggested)
📦 Customer-Shopping-Behavior-Analysis
│
├── data/
│   └── raw_data.csv
│
├── notebooks/
│   ├── data_cleaning.ipynb
│   └── exploratory_analysis.ipynb
│
├── sql/
│   └── business_queries.sql
│
├── powerbi/
│   └── dashboard.pbix
│
├── images/
│   └── dashboard_screenshots.png
│
└── README.md

🚀 How to Run the Project
1️⃣ Clone the repository
git clone https://github.com/Nakul-coder-2003/customer_shopping_analysis?tab=readme-ov-file

2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Run Python cleaning script
python data_cleaning.py

4️⃣ Execute SQL business queries

Import cleaned data into PostgreSQL and run business_queries.sql.

5️⃣ Open Power BI Dashboard

Load dashboard.pbix to explore insights.

🙌 Acknowledgements

This project demonstrates end-to-end analytics — Python → SQL → Power BI — suitable for real-world data analysis and business intelligence work.
