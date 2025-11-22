# 🛍️ Customer Shopping Behavior Analysis  
**Author:** Allen Arriaga  
**Date:** November 2025  
**Tools Used:** Python, SQL (PostgreSQL), Power BI, Data Cleaning, Feature Engineering, Exploratory Data Analysis  

---

## 📘 Overview  
This project analyzes customer shopping behavior using detailed transactional data from 3,900 purchases across multiple product categories.  

The goal was to uncover insights into spending habits, customer demographics, product preferences, discount usage, subscription behavior, and review ratings. Using Python, SQL, and Power BI, the analysis identifies what drives revenue, who the most valuable customers are, and which behaviors predict loyalty or high spending.

---

## 📊 Dataset  
**Rows:** 3,900  
**Columns:** 18  

### Key Features  
- **Demographics:** Age, Gender, Location, Subscription Status  
- **Purchase Details:** Item Purchased, Category, Purchase Amount, Season, Size, Color  
- **Behavior:** Discount Applied, Previous Purchases, Purchase Frequency, Review Rating, Shipping Type  
- **Missing Data:** 37 missing values in *Review Rating* (imputed using median per product category)

Data was cleaned and standardized in Python before modeling and SQL analysis.

---

## 🔍 Methods  

### 🧪 Exploratory Data Analysis (Python)  
- Loaded dataset using `pandas`  
- Cleaned missing review ratings using category-level medians  
- Standardized column names (snake_case)  
- **Feature Engineering:**  
  - `age_group` (binned by age)  
  - `purchase_frequency_days` (shopping frequency metric)  
- Removed redundant variables (`promo_code_used`)  
- Loaded cleaned dataset into PostgreSQL  

---

### 🗄️ SQL Analysis (Business Questions)  
Using PostgreSQL queries, the analysis explored:

1. Revenue by Gender  
2. High-Spending Discount Users  
3. Top 5 Products by Average Review Rating  
4. Standard vs. Express Shipping Purchase Amounts  
5. Subscribers vs. Non-Subscribers  
6. Products Most Dependent on Discounts  
7. New vs. Returning vs. Loyal Customer Segments  
8. Top 3 Products per Category  
9. Repeat Buyers and Subscription Likelihood  
10. Revenue by Age Group  

---

### 📊 Power BI Dashboard  
An interactive Power BI dashboard was created to visualize:

- Revenue by demographic segments  
- Seasonal sales patterns  
- Discount usage vs. profitability  
- Category and product performance  
- Customer loyalty and subscription behavior  

---

## 📈 Key Findings  
- **Subscribers** spend more and contribute more revenue.  
- **Express shipping customers** show higher spending tendencies.  
- **Frequent shoppers** tend to leave higher review ratings.  
- Some products rely heavily on **discount usage**, reducing margins.  
- The **25–34 age group** contributes a significant portion of total revenue.  
- Loyal customers (5+ purchases) are strongly associated with subscribing.

---

## 🧠 Business Recommendations  
- Increase **subscription incentives** to grow recurring revenue.  
- Strengthen **loyalty programs** to convert returning buyers into long-term customers.  
- Refine **discount strategy** to balance volume vs. margin.  
- Promote **top-rated products** more aggressively.  
- Target **high-value customer segments** in campaigns.

---

## 📄 View Full Analysis  
👉 [**View Full Analysis (PDF)**](/mnt/data/Customer Shopping Behavior Analysis.pdf)

---

