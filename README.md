# 💳 Credit Card Analysis Project

This project analyzes customer, credit profile, and transaction data to uncover insights about credit limits, age groups, and to identify the optimal target group for launching a new credit card.

---

## 📊 Project Objectives

- **Data Cleaning & Exploration:** Handle missing values and outliers in customer demographics, credit profiles, and transaction records.
- **Credit Limit Insights:** Explore the relationship between credit scores and credit limits, and treat anomalies in outstanding debt.
- **Age Group Analysis:** Segment customers by age, analyze their income, credit behavior, and transaction patterns.
- **Target Market Identification:** Use data-driven insights to recommend the best age group for a new credit card launch.

---

## 🗂️ Data Sources

- **Customers:** Demographic and income details.
- **Credit Profiles:** Credit scores, limits, and outstanding debts.
- **Transactions:** Purchase amounts, platforms, payment types, and product categories.

---

## 🔍 Key Insights

### 1. Data Cleaning & Preparation
- Missing values in income and age are imputed using occupation-wise medians.
- Outliers in annual income and age are treated for more accurate analysis.
- Duplicate and inconsistent credit profile entries are resolved.

### 2. Credit Limit & Score Analysis
- Credit limits are closely tied to credit scores.
- Outliers in outstanding debt are capped at the credit limit.
- Credit score ranges are created to better segment customers.

### 3. Age Group Segmentation
- Customers are grouped into: **18-25**, **26-48**, and **49-65**.
- The **26-48** age group forms the majority, but the **18-25** group is significant (~26%).
- Younger customers (18-25) have lower average income, credit limits, and credit scores.

### 4. Transaction Patterns
- Top product categories for 18-25: Electronics, Fashion & Apparel, Beauty & Personal Care.
- Preferred platforms: Amazon, Flipkart, Alibaba.
- Credit card usage is lower among the youngest group.

### 5. Target Group Recommendation
- **18-25 age group** is recommended for a trial credit card launch:
  - Represents a sizable portion of the customer base.
  - Lower income and credit history indicate potential for growth.
  - Distinct shopping preferences and lower current credit card usage present an opportunity.

---

## 📈 Technologies Used

- **Python** (Pandas, NumPy, Seaborn, Matplotlib)
- **Jupyter Notebook** for analysis and visualization

---

## 🚀 How to Use

1. Place datasets in the `dataset/` folder.
2. Open and run `Credit Card Analysis.ipynb` in Jupyter Notebook.
3. Review the visualizations and insights to understand customer segments and targeting strategy.

---

## 📝 Conclusion

This analysis provides a data-driven foundation for targeting the **18-25** age group for a new credit card product, maximizing the potential for customer acquisition