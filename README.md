# 📊 Customer Churn Analysis 

---

## 📊 Dashboard Preview

![Dashboard](images/dashboard.png)
![Customer Segmentation](images/customer_segmentation.png)
---
## 📌 Executive Summary

This project focuses on identifying customer churn risk and revenue loss using transactional data and RFM segmentation to drive retention strategies.

Key findings:

• ~33.4% of customers are at risk of churn, indicating a major retention challenge  
• High-value churn customers contribute disproportionately to revenue loss  
• A significant portion of revenue is concentrated among a small group of active customers  
• Customers with low engagement (high recency, low frequency) are the most vulnerable  

Business impact:

- Identifying at-risk customers enables targeted retention strategies
- Reducing churn can significantly increase customer lifetime value and revenue stability

---

## 💼 Business Problem

Businesses often struggle to identify customers who are likely to churn, leading to significant revenue loss.

This project analyzes customer transaction data to:

* Identify high-value customers
* Detect churn risk early
* Enable data-driven retention strategies

---

## 🚀 Project Overview

This is an end-to-end customer churn analysis project using **Python, SQL, and Power BI**.

The project focuses on understanding customer behavior using **RFM (Recency, Frequency, Monetary)** analysis and segmenting customers based on their engagement and value.

RFM analysis was used because it provides a simple yet effective way to quantify customer engagement and identify churn risk based on purchasing behavior.

---

## 🔍 Churn Definition

In this project, a customer is considered **churned** if they have not made a purchase in the last **90 days**.

This threshold is chosen based on customer purchase behavior patterns observed in the dataset.

- Active Customer → Recent purchase within 90 days  
- Churned Customer → No purchase in last 90+ days  

This approach reflects real-world business scenarios where inactivity signals potential churn risk.

---

## 🔄 Methodology

1. Data Cleaning using **Python (Pandas)**
2. SQL Analysis for business insights
3. RFM Feature Engineering
4. Customer Segmentation
5. Churn Identification
6. Data Visualization using **Matplotlib & Power BI**

---

## 🧠 Key Concepts Used

* RFM Analysis (Recency, Frequency, Monetary)
* Customer Segmentation
* Churn Detection
* SQL Aggregations & Queries
* Data Visualization

---

## 🛠️ Tools & Technologies

• Python (Pandas for data cleaning, Matplotlib for visualization)  
• SQL (aggregations, joins, customer-level analysis)  
• Power BI (interactive dashboards, KPI tracking, segmentation visualization)

---

## 📂 Dataset

The dataset is not included due to size limitations.

You can download it from:
https://archive.ics.uci.edu/ml/datasets/Online+Retail

---

## 📁 Project Structure

```
customer-churn-analysis/

│── data/
│   └── online_retail.csv

│── notebooks/
│   └── customer_churn_analysis.ipynb

│── images/
│   ├── dashboard.png
│   ├── customer_segmentation.png
│   ├── avg_revenue_by_segment.png
│   ├── customer_distribution.png
│   ├── revenue_by_segment.png
│   ├── churn_distribution.png
│   ├── rfm_scatter.png
│   ├── sql_top_customers.png
│   ├── sql_revenue_country.png
│   ├── sql_avg_order.png

│── README.md
```

---

## 📊 Dashboard

![Dashboard](images/dashboard.png)

---

## 📌 Customer Segmentation

![Customer Segmentation](images/customer_segmentation.png)

---

## 📈 Revenue Analysis

![Revenue by Segment](images/revenue_by_segment.png)

![Average Revenue by Segment](images/avg_revenue_by_segment.png)

---

## 👥 Customer Distribution

![Customer Distribution](images/customer_distribution.png)

---

## ⚠️ Churn Analysis & Behavior Patterns

![Churn Distribution](images/churn_distribution.png)

---

## 🔍 RFM Analysis

![RFM Scatter](images/rfm_scatter.png)

---

## 🧾 SQL Analysis

![Top Customers](images/sql_top_customers.png)

![Revenue by Country](images/sql_revenue_country.png)

![Average Order Value](images/sql_avg_order.png)

---

## 🎯 Key Insights

- A churn rate of ~33.4% indicates a significant drop-off in customer retention, requiring immediate intervention.
- High-value churn customers contribute disproportionately to revenue loss, making them the top priority for retention strategies.
- Customers with high recency (inactive for long periods) and low purchase frequency are at the highest risk of churn.
- Active customers generate the highest revenue, highlighting the importance of maintaining engagement.
- A large portion of customers fall into low-frequency segments, indicating potential for upselling and engagement campaigns.

---

## 💡 Business Impact

• Enables targeted retention campaigns for high-risk customers  
• Helps reduce revenue loss from churn  
• Improves customer lifetime value through segmentation-based strategies  

---

## 🧠 Retention Strategy Recommendations

Based on the analysis:

- 🎯 High-Value Churn Customers  
  → Offer personalized discounts and targeted re-engagement campaigns  

- 🔁 At-Risk Customers (high recency, low frequency)  
  → Send reminders, emails, and incentives to encourage repeat purchases  

- 💎 Loyal Customers  
  → Introduce loyalty programs and exclusive rewards to maintain engagement  

- 📉 Low-Value Customers  
  → Use low-cost automated marketing strategies to improve conversion  

These strategies can help reduce churn and increase customer lifetime value.

---

## ⚙️ How to Run

1. Clone the repository
2. Download dataset from the link above
3. Open the notebook in Jupyter or Google Colab
4. Run all cells step-by-step
5. View outputs and visualizations

---

## 📌 Conclusion

This project demonstrates how customer segmentation using RFM analysis can help businesses:

* Improve customer retention
* Increase lifetime value
* Make data-driven decisions

---

## 🚀 Future Enhancements

- Develop a machine learning model to predict churn probability at the individual customer level
- Implement real-time dashboards for continuous monitoring of churn risk
- Integrate customer feedback and behavioral data for deeper analysis
- Build automated retention campaigns based on customer segments

---
