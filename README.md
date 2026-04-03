# 📊 Customer Churn Analysis — Identifying At-Risk Customers & Improving Retention

## 📊 Dashboard Preview

![Dashboard](images/dashboard.png)

> 📌 Built using Power BI with interactive filters and RFM-based customer segmentation

---

## 📌 Executive Summary

This project analyzes customer behavior data to identify churn patterns and understand the key factors driving customer attrition.

Using RFM (Recency, Frequency, Monetary) segmentation and behavioral analysis, the project uncovers high-risk customer groups and highlights opportunities to improve retention strategies.

This project demonstrates how customer segmentation can be leveraged to reduce churn and maximize customer lifetime value.

---

## 📈 Why This Project Matters

Customer retention is more cost-effective than customer acquisition, yet many businesses fail to identify early churn signals.
This project highlights how customer segmentation and behavioral analysis can help reduce churn and improve long-term revenue.

---

## 💼 Business Problem

Businesses often struggle to retain customers due to lack of visibility into churn behavior. Without proper segmentation, companies cannot identify high-risk customers early.

This project aims to:

* Identify customers likely to churn
* Analyze behavioral patterns leading to churn
* Segment customers based on value and engagement

---

## ❓ Key Business Questions

* Which customers are most likely to churn?
* What behavioral patterns indicate churn risk?
* Which customer segments generate the most value?
* How can businesses reduce churn effectively?

---

## 🚀 Project Overview

This is an end-to-end customer churn analysis project using Python, SQL, and Power BI.

The analysis focuses on customer segmentation using RFM (Recency, Frequency, Monetary) and identifying churn risk patterns.

The goal is to enable proactive retention strategies instead of reactive churn handling.

---

## 📊 Visualization Summary

The Power BI dashboard provides insights into customer segments, churn risk, and behavioral trends.

Key visuals include:

* Customer segmentation (RFM-based)
* Churn distribution across segments
* Revenue contribution by customer groups
* Behavioral trends leading to churn

---

## 📊 Dashboard Breakdown

- KPI Cards → Show overall churn rate, revenue, and total customers
- Segment Distribution → Identify high-risk customer groups
- Revenue by Segment → Understand business impact of each segment
- Behavioral Trends → Detect patterns leading to churn

## 📌 Customer Segmentation

![Customer Segmentation](images/customer_segmentation.png)

Insight:

This visualization highlights different customer segments based on RFM scores. High-value segments contribute significantly to revenue but may show early signs of churn, requiring targeted retention strategies.
---

## 📈 Revenue Analysis

![Revenue by Segment](images/revenue_by_segment.png)

![Average Revenue by Segment](images/avg_revenue_by_segment.png)

Insight:

Revenue is heavily concentrated among a few key segments. While high-value customers generate the most revenue, some segments show declining engagement, indicating potential revenue risk.
---

## 👥 Customer Distribution

![Customer Distribution](images/customer_distribution.png)
Insight:

This chart shows how customers are distributed across segments. A higher proportion of low-engagement customers suggests potential churn risk and opportunity for re-engagement campaigns.
---

## ⚠️ Churn Analysis & Behavior Patterns

![Churn Distribution](images/churn_distribution.png)

Insight:

Churn is more prevalent among customers with low purchase frequency and long inactivity periods. This confirms behavioral patterns as strong indicators of churn risk.
---

## 🔍 RFM Analysis

![RFM Scatter](images/rfm_scatter.png)

Insight:

The RFM scatter plot helps identify clusters of high-value and at-risk customers. Customers with low recency and frequency are more likely to churn, while frequent buyers show higher retention.
---

## 🧾 SQL Analysis

![Top Customers](images/sql_top_customers.png)

![Revenue by Country](images/sql_revenue_country.png)

![Average Order Value](images/sql_avg_order.png)

Insight:

SQL analysis validates key findings by identifying top revenue-generating customers, regional performance differences, and average order value trends, supporting data-driven decision-making.

---

## 🎯 Key Insights

- High churn rate (~33%) indicates significant revenue leakage and urgent need for retention strategies  
- High-value customers contribute the majority of revenue but show early signs of disengagement, posing a major business risk  
- Customers with low purchase frequency and long inactivity periods are the most likely to churn  
- Repeat purchase behavior is strongly correlated with retention, making it a key metric for engagement strategies  
- Certain customer segments exhibit declining engagement patterns before churn, enabling early intervention opportunities  

---

## 💡 Business Impact

* Enables early identification of high-risk customers
* Helps prioritize retention efforts for high-value segments
* Improves customer lifetime value (CLV)
* Supports proactive decision-making instead of reactive churn management

---

## 💡 Recommendations

- Prioritize retention of high-value customers through personalized offers and loyalty programs  
- Target at-risk customers using re-engagement campaigns (email, discounts, reminders)  
- Increase purchase frequency with subscription models or repeat incentives  
- Focus marketing efforts on high lifetime value (LTV) segments instead of low-value users  
- Implement early warning systems using RFM segmentation to detect churn risk proactively  

---

## 🛠️ Tools Used

* Python (Pandas)
* SQL
* Power BI
* DAX

---

## ⚙️ Technical Highlights

* Performed data cleaning and preprocessing (handling missing values, type conversions)
* Implemented RFM (Recency, Frequency, Monetary) segmentation
* Conducted exploratory data analysis to identify churn patterns
* Built calculated measures in Power BI using DAX
* Designed an interactive dashboard with filters and drill-down capabilities

---

## 🔄 Project Workflow

1. Data Loading
   Loaded customer dataset using Python

2. Data Understanding
   Explored structure, missing values, and duplicates

3. Data Cleaning
   Handled inconsistencies and prepared dataset for analysis

4. Feature Engineering
   Created RFM metrics (Recency, Frequency, Monetary)

5. Customer Segmentation
   Grouped customers based on behavioral patterns

6. Churn Analysis
   Identified high-risk customer segments

7. Visualization
   Built Power BI dashboard with KPIs and segmentation insights

---

## 📂 Files Included

* `python/customer_churn_analysis.ipynb`
* `data/customer_data.csv`
* `Customer_Churn_Dashboard.pbix`
* `images/dashboard.png`

---

## 📌 Conclusion

Customer churn is not random — it follows identifiable behavioral patterns.
By leveraging segmentation techniques like RFM, businesses can proactively reduce churn and improve long-term customer value.

---

## 📚 Key Learnings

* Customer segmentation is critical for retention strategies
* Behavioral patterns can predict churn risk early
* Data-driven retention strategies improve customer lifetime value
* End-to-end analytics involves data cleaning, segmentation, and storytelling
