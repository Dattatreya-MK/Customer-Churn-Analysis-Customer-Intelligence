# Customer-Churn-Analysis-Customer-Intelligence
End-to-end customer churn analysis using SQL, Python, Pandas, NumPy, SQLite, Matplotlib and Seaborn to identify churn patterns, customer risk segments, revenue at risk and retention opportunities.
# Customer Churn Analysis & Customer Intelligence

## 📌 Project Overview

This project focuses on analyzing customer churn for an OTT subscription platform using SQL and Python. The objective is to identify customer churn patterns, understand the factors associated with churn, segment customers based on churn risk, and quantify the potential revenue impact.

The project follows an end-to-end data analytics workflow, starting from relational database extraction and data cleaning to feature engineering, exploratory data analysis, visualization, and business recommendations.

## 🛠️ Tech Stack

- Python
- SQL
- SQLite
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🗂️ Dataset Structure

The SQLite database contains three relational tables:

- `db_customer` – Customer demographic information
- `db_subscription` – Subscription, plan, contract, charges and churn information
- `db_support` – Complaints, escalations and CSAT information

The tables were joined using `customerid` to create an analytical dataset.

## 🔄 Project Workflow

1. Connected SQLite database with Python
2. Extracted relational tables using SQL queries
3. Performed data quality checks
4. Cleaned and standardized customer data
5. Handled missing values
6. Converted date columns into appropriate formats
7. Created a churn flag
8. Removed duplicate support records
9. Joined customer, subscription and support datasets
10. Engineered tenure and churn-risk features
11. Performed exploratory data analysis
12. Calculated key business KPIs
13. Created visualizations using Matplotlib and Seaborn
14. Generated business insights and retention recommendations

## 📊 Key KPIs

- Churn Rate
- Retention Rate
- Churn by Plan Type
- Churn by State
- ARPU
- Average Customer Tenure
- Revenue at Risk
- Escalation Rate
- Average Complaints per Customer
- Correlation between Support Escalations and Churn
- Customer Churn Risk

## 📈 Key Findings

- Overall churn rate: **28.6%**
- Retention rate: **71.4%**
- Monthly-contract churn: **55.6%**
- Annual-contract churn: **8.3%**
- Revenue loss due to churn: approximately **₹74K/month**
- CLTV lost: approximately **₹2,047K**
- Revenue loss represented approximately **18%**
- Karnataka showed the highest churn concentration.
- September 2024 recorded the highest churn concentration.

## 💡 Business Recommendations

- Investigate the increase in churn in Karnataka.
- Analyze pricing and product changes affecting Basic-plan customers.
- Prioritize high- and medium-risk customers for retention campaigns.
- Investigate customer complaints and support escalations.
- Encourage migration from monthly to annual contracts where appropriate.
- Prioritize retention efforts based on customer lifetime value.

## 🎯 Business Impact

The analysis provides a data-driven framework for identifying high-risk customers and prioritizing retention efforts. The findings can help subscription businesses reduce revenue leakage, improve customer retention and focus customer-success resources on the highest-value at-risk customers.

## 📁 Project Files

- `customer_churn.db` – SQLite database
- `customer_churn_analysis.ipynb` – Python/Jupyter analysis
- `customer_churn_data_raw.xlsx` – Raw dataset
- `Data Analytics Project -Churn Analysis Report.pdf` – Project report
