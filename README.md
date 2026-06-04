# 🛍️ Customer Behavior Analytics & Segmentation

## 📌 Project Overview

Customer Behavior Analytics & Segmentation is an end-to-end Data Analytics project that analyzes retail transaction data to uncover customer purchasing patterns, identify high-value customers, and generate actionable business insights.

The project combines **Python, Machine Learning, and Power BI** to transform raw transactional data into strategic business recommendations.

---

## 🎯 Business Problem

Businesses often struggle to understand:

* Which customers generate the most revenue?
* Which customers are likely to stop purchasing?
* What products drive sales performance?
* How can customer retention be improved?
* Which customer segments should receive targeted marketing campaigns?

This project addresses these challenges using customer analytics and segmentation techniques.

---

## 📊 Project Objectives

* Analyze customer purchasing behavior.
* Identify high-value and at-risk customers.
* Perform RFM (Recency, Frequency, Monetary) analysis.
* Segment customers using K-Means Clustering.
* Build interactive dashboards for business decision-making.
* Generate actionable recommendations to improve customer retention and revenue.

---

## 🗂️ Dataset Information

**Dataset:** Online Retail Dataset

| Metric           | Value   |
| ---------------- | ------- |
| Original Records | 525,461 |
| Cleaned Records  | 400,916 |
| Customers        | 4,312   |
| Orders           | 19,000+ |
| Revenue          | 8.8M+   |

### Key Features

* Invoice Number
* Customer ID
* Product Description
* Quantity
* Unit Price
* Revenue
* Country
* Invoice Date

---

## 🛠️ Technologies Used

### Programming & Analysis

* Python
* Pandas
* NumPy
* Scikit-Learn

### Data Visualization

* Matplotlib
* Seaborn
* Power BI

### Development Tools

* Jupyter Notebook
* VS Code
* GitHub

---

## 🔄 Project Workflow

```text
Raw Data
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis (EDA)
   ↓
Feature Engineering
   ↓
RFM Analysis
   ↓
Customer Segmentation
   ↓
K-Means Clustering
   ↓
Power BI Dashboard
   ↓
Business Recommendations
```

---

## 🧹 Data Cleaning

The following preprocessing steps were performed:

* Removed missing Customer IDs
* Removed missing product descriptions
* Removed duplicate transactions
* Removed negative quantities and invalid prices
* Created Revenue feature
* Extracted Year, Month, and Day features
* Standardized data types

Final cleaned dataset contained **400,916 records**.

---

## 📈 Exploratory Data Analysis (EDA)

Key analyses performed:

* Revenue Trends
* Monthly Sales Performance
* Product Performance Analysis
* Country-wise Revenue Analysis
* Customer Spending Behavior
* Order Frequency Analysis

### Key Insights

* Revenue exceeded **8.8 Million**.
* November generated the highest revenue.
* United Kingdom contributed the majority of sales.
* Revenue increased significantly during Q4.
* Sales were concentrated among a small group of customers.

---

## 🎯 RFM Analysis

Customers were evaluated using:

### Recency (R)

How recently a customer made a purchase.

### Frequency (F)

How often a customer purchases.

### Monetary (M)

How much revenue a customer generates.

RFM scoring was used to classify customers into meaningful business segments.

---

## 🤖 Customer Segmentation

### Business Segments

* 🏆 Champions
* ⭐ Loyal Customers
* 📘 Regular Customers
* ⚠️ At-Risk Customers

### Segmentation Insights

* Champions generated the highest customer value.
* Loyal Customers contributed significant recurring revenue.
* At-Risk Customers represented the largest segment.
* Regular Customers showed growth potential.

---

## 🧠 K-Means Clustering

Machine learning was applied using K-Means Clustering to group customers based on:

* Recency
* Frequency
* Monetary Value

The clustering model helped identify customer groups with similar purchasing behavior and supported targeted business recommendations.

---

## 📊 Power BI Dashboard

The dashboard consists of four interactive pages:

### 1️⃣ Executive Overview

* Revenue KPIs
* Revenue Trends
* Top Countries
* Top Products

### 2️⃣ Sales Analysis

* Revenue vs Orders
* Monthly Sales Trends
* Revenue Heatmaps
* Seasonal Analysis

### 3️⃣ Customer Analytics

* Customer Distribution
* Purchase Frequency
* Customer Value Analysis
* Top Customers

### 4️⃣ Segmentation & Clustering

* Segment Distribution
* Cluster Analysis
* RFM Performance
* Customer Action Plans

---

## 📷 Dashboard Preview

### Executive Overview

![Executive Dashboard](dashboard/page1.png)

### Sales Analysis

![Sales Analysis](dashboard/page2.png)

### Customer Analytics

![Customer Analytics](dashboard/page3.png)

### Segmentation & Clustering

![Segmentation Dashboard](dashboard/page4.png)

---

## 💡 Business Recommendations

### 🏆 Champions

* Offer loyalty rewards.
* Provide VIP benefits.
* Early access to promotions.

### ⭐ Loyal Customers

* Cross-sell and upsell products.
* Personalized product recommendations.

### 📘 Regular Customers

* Increase engagement through targeted campaigns.
* Encourage repeat purchases.

### ⚠️ At-Risk Customers

* Launch reactivation campaigns.
* Offer retention discounts.
* Send personalized reminders.

---

## 🚀 Future Improvements

* Customer Churn Prediction
* Customer Lifetime Value (CLV) Prediction
* Product Recommendation System
* Real-Time Dashboard Integration
* Automated ETL/Data Pipeline
* Deployment as a Web Analytics Application

---

## 👨‍💻 Author

**Vignesh L**

Aspiring Data Analyst | Python | SQL | Power BI | Machine Learning

