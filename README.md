# 🛍️ Customer Behavior Analysis

An end-to-end Data Analytics project that analyzes retail customer shopping behavior to uncover purchasing trends, customer segments, and revenue drivers. The project demonstrates the complete analytics workflow—from data cleaning and exploration in Python, SQL analysis in MySQL, dashboard development in Power BI, to presenting business insights through a professional report and presentation.

---

## 📖 Project Overview

A retail company wants to better understand its customers' shopping behavior to improve customer engagement, optimize marketing strategies, and increase long-term profitability.

This project answers the business question:

> **"How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?"**

---

## 📂 Dataset

**Dataset:** Customer Shopping Behavior Dataset

**Dataset Summary**

- **Records:** 3,900
- **Features:** 18
- Customer Demographics
- Purchase Details
- Shopping Behavior
- Customer Reviews
- Discounts & Subscription Information

---

## 🛠️ Tools & Technologies

- **Python**
  - Pandas
  - SQLAlchemy
  - PyMySQL

- **MySQL Workbench**

- **Power BI**

- **Gamma** (Presentation)

- **Microsoft Word** (Project Report)

---

## 📊 Project Workflow

### 1. Data Loading
- Imported the dataset into Python using Pandas.
- Performed initial data inspection and exploratory analysis.

### 2. Data Cleaning & Feature Engineering
- Checked missing values.
- Imputed missing review ratings using category median.
- Standardized column names.
- Created:
  - `age_group`
  - `purchase_frequency_days`
- Removed redundant columns.
- Exported the cleaned dataset to MySQL.

### 3. SQL Analysis
Performed business analysis using MySQL, including:

- Revenue by gender
- Discount effectiveness
- Highest-rated products
- Subscription spending analysis
- Customer segmentation
- Revenue by age group
- Top-performing products
- Shipping preference analysis

### 4. Dashboard Development
Built an interactive Power BI dashboard to visualize:

- Total Customers
- Average Purchase Amount
- Average Review Rating
- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Sales by Age Group
- Subscription Distribution

Interactive filters include:

- Gender
- Subscription Status
- Category
- Shipping Type

<p align="center">
  <img src="dashboard.png" alt="Power BI Dashboard" width="1000"/>
</p>

### 5. Business Reporting
Created:
- Professional project report
- Business presentation using Gamma

---

## 🔍 Key Insights

- Subscription customers generated higher revenue than non-subscribers.
- Adult and middle-aged customers contributed the highest revenue.
- Discounts influenced purchasing decisions for several products.
- Loyal customers represented a significant share of repeat purchases.
- Highly rated products present strong cross-selling and promotional opportunities.

---

## 💡 Business Recommendations

- Expand customer loyalty programs.
- Personalize discount campaigns.
- Strengthen subscription benefits.
- Promote highly rated products.
- Develop targeted marketing campaigns based on customer demographics.
- Optimize inventory using product demand insights.

---

## 📁 Repository Structure

```
Customer-Behavior-Analysis/
│
├── Dataset/
│   └── customer_shopping_behavior.csv
│
├── Python/
│   └── customer_behavior_analysis.ipynb
│
├── SQL/
│   └── customer_behavior_analysis.sql
│
├── PowerBI/
│   └── Customer_Behavior_Dashboard.pbix
│
├── Report/
│   └── Customer_Behavior_Analysis_Report.pdf
│
├── Presentation/
│   └── Customer_Behavior_Analysis_Presentation.pdf
|
├── Assets/
│   └── dashboard.png
|
└── README.md
```

---

## ▶️ How to Run

1. Clone this repository.
2. Open the Python notebook and install the required libraries.
3. Run the data cleaning and preprocessing steps.
4. Export the cleaned dataset to MySQL.
5. Execute the SQL queries in MySQL Workbench.
6. Open the Power BI (`.pbix`) file to explore the interactive dashboard.
7. Review the project report and presentation for business insights.

---

## 🎯 Project Outcomes

This project demonstrates practical skills in:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- SQL Querying
- Business Intelligence
- Dashboard Design
- Data Storytelling
- Business Recommendations

---

## 👤 Author

**Adhya Rastogi**

MBA in Business Analytics | Data Analytics | Business Intelligence

**LinkedIn:** https://www.linkedin.com/in/adhyarastogi/
