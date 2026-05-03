# 📊 Customer Segmentation using RFM Analysis

## 📌 Project Overview

This project performs customer segmentation using RFM (Recency, Frequency, Monetary) analysis on an online retail dataset. The goal is to identify high-value customers, understand purchasing behavior, and provide actionable business insights.

---

## 🧠 Problem Statement

Businesses often struggle to identify their most valuable customers. This project aims to segment customers based on their transaction history to support targeted marketing and retention strategies.

---

## ⚙️ Approach

### 1. Data Cleaning

* Removed negative quantities (returns)
* Dropped missing Customer IDs
* Converted date columns into datetime format

### 2. Feature Engineering

* Created TotalPrice column
* Calculated:

  * Recency (last purchase)
  * Frequency (number of purchases)
  * Monetary (total spending)

### 3. RFM Scoring

* Customers were scored using quantiles
* Combined R, F, and M scores into a final RFM score

### 4. Customer Segmentation

Customers were segmented into:

* High Value Customers
* Medium Value Customers
* Low Value Customers

---

## 📊 Key Insights

* High-value customers contribute a major portion of total revenue
* Customers with high recency are at risk of churn
* Medium-value customers have strong growth potential

---

## 💡 Business Recommendations

* 🎯 High Value → Loyalty programs & exclusive offers
* 📈 Medium Value → Targeted promotions & upselling
* ⚠️ Low Value → Re-engagement campaigns & discounts

---

## 🛠️ Tools Used

* Python
* Pandas

---

## 🚀 Conclusion

This project demonstrates how data-driven techniques can help businesses understand customer behavior and improve decision-making through segmentation.
