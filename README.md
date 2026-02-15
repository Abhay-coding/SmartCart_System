# 🛒 SmartCart Clustering System

## 📌 Project Overview

SmartCart Clustering System is an **unsupervised machine learning project** designed to perform intelligent customer segmentation for an e-commerce platform.

The main objective is to discover hidden customer groups based on purchasing behaviour, engagement level, and loyalty indicators so that businesses can make **data-driven decisions** instead of using generic marketing strategies.

---

## ❗ Problem Statement

SmartCart currently applies the same marketing strategy to all customers, which leads to:

- Inefficient marketing campaigns  
- Poor targeting of high-value customers  
- Delayed identification of churn-prone users  

This project solves the problem using **clustering algorithms** to generate meaningful customer segments.

---

## 📊 Dataset Description

- **Total Records:** 2240 customers  
- **Total Features:** 22 attributes  

Each row represents one customer profile.

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

### 🔹 Customer Feedback
- Recency  
- Complain  

---

## ⚙️ Project Workflow

1. Handle Missing Data  
2. Feature Engineering  
3. Drop Irrelevant Columns  
4. Handle Outliers  
5. Feature Correlation Heatmap  
6. Feature Encoding & Scaling  
7. Data Visualization  
8. Choose Optimal K (Elbow Method & Silhouette Score)  
9. Clustering / Segmentation  
10. Cluster Characterization  
11. Cluster Profiling Summary  

---

## 🧠 Algorithms & Techniques Used

- K-Means Clustering  
- Elbow Method  
- Silhouette Score  
- Feature Scaling (StandardScaler / MinMaxScaler)  
- Encoding (Label Encoding / One-Hot Encoding)  
- Data Visualization  

---

## 📈 Cluster Outcomes (Model Results)

After applying K-Means clustering, customers were segmented into **4 distinct clusters**.

### 🔹 Cluster Profiling Summary

| Cluster | Avg Income | Avg Total Spending | Web Purchases | Store Purchases | Web Visits | Response Rate | Interpretation |
|---|---|---|---|---|---|---|---|
| 0 | ~39K | Low (~222) | Low | Medium | High | Low | Low-value / Browsing Customers |
| 1 | ~72K | High (~1237) | High | High | Low | Medium | High-value Loyal Customers |
| 2 | ~37K | Very Low (~166) | Low | Low | High | Low | Low Engagement Customers |
| 3 | ~70K | High (~1190) | High | High | Low | High | Premium & Responsive Customers |

---

### 📊 Observations

- **Clusters 1 & 3** represent high-income, high-spending customers.  
- **Cluster 3** shows the highest campaign response → ideal for premium marketing.  
- **Cluster 0 & 2** show low spending but high website visits → potential churn or window shoppers.  
- Web visits are inversely related to purchase activity in higher-value clusters.

---

## 🛠️ Tech Stack

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  





