# 🛒 SmartCart Clustering System

## 📌 Project Overview
SmartCart Clustering System is an **unsupervised machine learning project** designed to perform intelligent customer segmentation for an e-commerce platform.

The goal is to identify hidden customer groups using clustering techniques so that businesses can:

- Improve marketing strategies
- Increase customer retention
- Personalize customer engagement
- Identify high-value and churn-prone customers

The system analyzes historical customer transaction data and groups customers based on purchasing behavior, engagement, and loyalty patterns.

---

## ❗ Problem Statement
SmartCart currently uses **generic marketing strategies** for all customers, which leads to:

- Inefficient marketing campaigns  
- Missed opportunities for targeting valuable customers  
- Delayed identification of churn-prone users  

This project solves the problem using **unsupervised machine learning (clustering)** to generate meaningful customer segments for data-driven decision making.

---

## 📊 Dataset Description

- **Total Records:** 2240 customers  
- **Total Features:** 22 attributes  

Each row represents a customer profile containing demographic information, purchase behavior, and engagement details.

### 🔹 Customer Demographics
- Year_Birth
- Education
- Marital_Status
- Income
- Kidhome
- Teenhome
- Dt_Customer

### 🔹 Purchase Behaviour (Amount Spent)
- MntWines
- MntFruits
- MntMeatProducts
- MntFishProducts
- MntSweetProducts
- MntGoldProds

### 🔹 Purchase Behaviour (Frequency)
- NumDealsPurchases
- NumWebPurchases
- NumCatalogPurchases
- NumStorePurchases
- NumWebVisitsMonth

### 🔹 Customer Feedback & Constants
- Recency
- Complain

---

## ⚙️ Project Pipeline

1. Handle Missing Data  
2. Feature Engineering  
3. Drop Irrelevant Columns  
4. Handle Outliers  
5. Feature Correlation Heatmap  
6. Feature Encoding & Scaling  
7. Data Visualization  
8. Choose Optimal K (Elbow Method & Silhouette Score)  
9. Clustering / Segmentation  
10. Characterization of Clusters  
11. Cluster Summary for Profiling  

---

## 🧠 Algorithms & Techniques Used

- K-Means Clustering
- Elbow Method
- Silhouette Score
- Feature Scaling (StandardScaler / MinMaxScaler)
- Encoding (Label Encoding / One-Hot Encoding)
- Data Visualization

---

## 📈 Key Outcomes

- Customers segmented into meaningful clusters
- Identification of:
  - High-value customers
  - Discount-driven customers
  - Low engagement users
  - Potential churn segments
- Improved business understanding of customer behavior

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn


