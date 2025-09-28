# 🛒 E-Commerce Customer Analysis  

This project analyzes **34,500 e-commerce transaction records** with the goal of understanding sales patterns, customer behavior, and segmenting customers using clustering methods.  

## 📌 Project Objectives  
- Perform **data cleansing** (check consistency, handle missing values, validate calculations).  
- Conduct **Exploratory Data Analysis (EDA)** to identify sales patterns.  
- Apply **Customer Segmentation** using **K-Means Clustering** based on **RFM (Recency, Frequency, Monetary)**.  

## 📊 Dataset  
- Number of records: 34,500 transactions  
- Key columns: Customer ID, Product Category, Quantity, Revenue, Profit, Order Date  

*(Dataset is not included due to confidentiality. Please use your own dataset for replication.)*  

## 🔎 Analysis & Insights  
- **Product Categories**  
  - Electronics → major contributor to revenue, profit, and quantity.  
  - Home Appliance & Sport → strong in profit.  
  - Fashion → leads in quantity.  
  - Grocery → high in quantity but negative profit.  

- **Time Patterns**  
  - Sales spikes occur in **May** and at the **end of the year** (2024 & 2025).  
  - Transactions are spread evenly across the week (7 days), with no dominant day.  

- **Customer Segmentation (K=3)**  
  - **Big Spenders** → High-value transactions, low frequency → suitable for rewards & exclusive campaigns.  
  - **Active Spenders** → Significant customer base, indicator of a healthy e-commerce → should focus on loyalty retention.  
  - **Lost Customers** → Nearly 50% compared to active customers → requires *win-back* strategies.  

## 🛠️ Tools & Libraries  
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn (K-Means Clustering) 
