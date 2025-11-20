# 🛍️ Customer Shopping Behavior Analysis  
### *A Data Analysis Project using Python, SQL, and Power BI*

---

## 📌 Project Overview  
This project analyzes **3,900+ customer transactions** to uncover insights related to spending behavior, customer segments, product preferences, and subscription patterns.  
It follows a complete **end-to-end data analytics workflow** — from data cleaning (Python) to business analysis (SQL) and final visualization (Power BI).

---

## 📂 Dataset Summary  

- **Rows:** 3,900  
- **Columns:** 18  
- **Key Features:**  
  - 👥 Customer demographics — *Age, Gender, Location, Subscription Status*  
  - 🛒 Purchase details — *Item, Category, Amount, Season, Size, Color*  
  - 📦 Shopping behavior — *Discounts, Promo Codes, Previous Purchases, Frequency, Review Rating, Shipping Type*  
- **Missing Data:** 37 missing values in *Review Rating* column (handled during cleaning)

---

## 🧹 Data Cleaning & Transformation (Python)

Performed using **Pandas**, **NumPy**, and **PostgreSQL connection**.

### ✔ Key Steps  
- Loaded and explored dataset (`df.info()`, `df.describe()`)  
- Imputed missing review ratings using **median per category**  
- Standardized all column names to **snake_case**  
- Engineered new features:  
  - `age_group`  
  - `purchase_frequency_days`  
- Removed redundant column: `promo_code_used`  
- Loaded cleaned data into **PostgreSQL** for SQL analysis  

---

## 🧠 SQL Analysis – Business Insights  

Using PostgreSQL, several real-world business questions were answered:

- Revenue breakdown by **gender**  
- Customers using **discounts** but spending above average  
- **Top 5** highest-rated products  
- Comparison of purchase amount: **Standard vs Express Shipping**  
- Subscriber vs Non-subscriber **spending comparison**  
- Most **discount-dependent** products  
- Customer segmentation: **New / Returning / Loyal**  
- **Top 3 products** within each category  
- Repeat buyers & likelihood of subscription  
- Revenue contribution by **age group**

---

## 📊 Power BI Dashboard  

Interactive dashboard includes:

- 📈 Revenue trends  
- 👥 Customer segmentation  
- 🛒 Product performance  
- 🔔 Subscription insights  
- 🌎 Demographic breakdowns  

---

## 💡 Business Recommendations  

- Promote **subscription benefits**  
- Strengthen **loyalty programs**  
- Optimize **discount policies**  
- Highlight **top-rated & best-selling** products  
- Target marketing to profitable **age groups** and **express-shipping users**

---

## 🛠️ Tech Stack  

| Skill | Tools Used |
|-------|------------|
| **Data Cleaning & Preparation** | Python, Pandas, NumPy |
| **Feature Engineering** | Python |
| **Database & Querying** | PostgreSQL, SQL |
| **Business Insights** | SQL |
| **Data Visualization** | Power BI |
| **Version Control** | GitHub |

---

## 📁 Repository Structure  

