# 👥 Customer Segmentation & Value Insights Dashboard

An interactive Power BI analytics suite analyzing 50,000 customers and 5 million transactions to identify high-value cohorts, analyze purchasing patterns, and evaluate behavioral demographics for targeted marketing.

---

## 📊 Dashboard Overview

### Page 1: Customer Segmentation & Value Insights
![Page 1 Overview](CUSTOMER%20PRO%20PAGE%201.jpg)

* **Total Customers:** 50K
* **Total Revenue:** $2.51 Billion
* **Total Purchases:** 5 Million
* **Top Revenue City:** Singapore ($156M)
* **Core Segment Performance:** Core customers generate the bulk of total revenue ($1,521.04M), despite moderate value and inactive users comprising larger portions of the customer base.

---

### Page 2: Behavioral Overview
![Page 2 Behavioral Overview](CUSTOMER%20PRO%20PAGE%202.jpg)

* **Average Age:** 46 years
* **Average Order Value (AOV):** $505.37
* **Average Tenure:** 59.75 months (~5 years)
* **Average Recency:** 3.95
* **Behavioral Dynamics:** High-value tier leads with an average order value of $817, followed by Core customers ($677). Purchase frequency exhibits strong exponential correlation with higher frequency scores.

---

## 🎯 Key Business Questions Solved

* **Who drives the revenue?** Breaks down customer tiers into *High-value Tier*, *Core Customers*, *Moderate Value*, and *Inactive* groups to track total monetary yield and AOV.
* **Where is geographic demand concentrated?** Evaluates revenue performance across top urban hubs (Singapore, Newcastle, Abu Dhabi, Sharjah, Ajman, Dubai, etc.).
* **How balanced are sales channels?** Evaluates payment channel distribution across Credit Card, Debit Card, Bank Transfer, Cash on Delivery, and Digital Wallet (each accounting for ~20% share).
* **Which product lines capture spend?** Details revenue contribution across primary categories including Electronics, Automotive, Office Supplies, and Pet Supplies.

---

## 🛠️ Tech Stack & Methods

* **Business Intelligence:** Microsoft Power BI Desktop
* **Data Prep & ETL:** Power Query (type casting, blank handling, deduplication)
* **Data Modeling:** Star schema relational design with custom DAX aggregations and measures
* **Visualization Formats:** Donut charts, Treemaps, Bar & Column rankings, Area charts, and KPI metric cards

---

## 💡 Strategic Takeaways

1. **Protect the High-Value Tier:** While smaller in count (6.06% of base), their $817 AOV makes retention, VIP priority services, and exclusive loyalty programs top ROI priorities.
2. **Reactivate the Inactive Pool:** Inactive customers make up 16.72% of users ($307.03M past revenue), indicating a prime opportunity for automated win-back and discount trigger workflows.
3. **Even Payment Preference:** Uniform split (~20% each) across credit cards, bank transfers, COD, and digital wallets suggests checkout flexibility is essential across all regional markets.

---

## 🚀 How to Run Locally

1. Clone this repository:
   ```bash
   git clone [https://github.com/amaldev7090/Customer-segmentation-Dashboard.git](https://github.com/amaldev7090/Customer-segmentation-Dashboard.git)
