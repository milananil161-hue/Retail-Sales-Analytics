# Retail Sales Analytics & Customer Segmentation

This project performs detailed analysis of retail transaction data to extract business insights, understand customer behaviour, identify high-value segments, and derive product-level performance. Machine learning-based clustering is applied to group customers into meaningful categories to support targeted business strategies.

## 📌 Project Objectives

✔ Clean and preprocess retail datasets  
✔ Analyze monthly revenue trends  
✔ Evaluate customer purchase behaviour  
✔ Identify top revenue generating customers  
✔ Cluster customers using Machine Learning  
✔ Derive insights for managerial decisions  

## 🗂 Dataset Overview

The dataset includes retail transaction records with the following primary attributes:

| Column | Description |
|--------|-------------|
| CustomerID | Unique customer identifier |
| ProductID | Purchased product |
| Quantity | Number of items purchased |
| Price | Unit price |
| TransactionDate | Date of purchase |
| PaymentMethod | Payment mode |
| DiscountApplied(%) | Discount given |
| TotalAmount | Final billed amount |

A derived metric is calculated as:  
```
TotalAmount = Quantity × Price
```

## 📁 Project Folder Structure

```
Retail-Sales-Analytics/
│
├── data/
│   ├── retail.csv
│   ├── cleaned_retail.csv
│
├── notebooks/
│   └── retail_analysis.ipynb
│
├── reports/
│   └── Retail_Sales_Report.pdf
│
├── visuals/
│   ├── monthly_trend.png
│   ├── segmentation_plot.png
│   ├── top_customers.png
│   └── heatmap.png
│
└── README.md
```

## 🛠 Tools and Technologies

| Category | Tools Used |
|----------|-------------|
| Programming | Python |
| Libraries | Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn |
| Notebook | Jupyter Notebook |
| Visualization | Line charts, bar charts, heatmaps, scatter plots |

## 🚀 How to Run This Project

### Step 1: Install required libraries
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Step 2: Launch Jupyter Notebook
```bash
jupyter notebook
```

### Step 3: Run the notebook
Open file:
```
notebooks/retail_analysis.ipynb
```

## 📊 Key Features of the Analysis

### 🟣 Revenue Trend Analysis
- Monthly revenue peaks between **May and January**
- Drop observed during **February & April**
- Indicates seasonal purchasing behaviour

### 🟢 Customer Segmentation (K-Means)
Three clusters identified:

| Cluster | Spend Level | Buying Behaviour |
|----------|-------------|------------------|
| Cluster 1 | Highest | Frequent buyers, high loyalty |
| Cluster 0 | Medium | Average spend, repeat buyers |
| Cluster 2 | Lowest | One-time buyers / bargain seekers |

### 🔵 Product Performance
- Products **D and C** contribute most revenue
- Product **A needs marketing push or repositioning**
- Bulk purchase directly increases revenue

### 🔴 Discount Impact
- Discount % shows weak correlation with total revenue  
→ Customers are not motivated mainly by discounting  
→ Loyalty/value propositions more effective

## 📈 Visual Outputs

This project generates:

✔ Revenue trend line chart  
✔ Top 10 customer contribution graph  
✔ Customer segmentation scatter plot  
✔ Correlation heatmap  
✔ Price distribution histogram  

These images are available under `/visuals/`.

## 🎯 Business Insights

From the analysis:

⭐ 20% of customers generate majority revenue  
⭐ Premium customers must be retained through loyalty programs  
⭐ Low-value customers require reactivation campaigns  
⭐ Bundling products improves AOV (Average Order Value)  
⭐ Seasonal demand should drive stock planning  

## 🔎 Future Enhancements

🔹 Basket-wise recommendation engine  
🔹 Forecasting models (XGBoost / Prophet)  
🔹 Customer churn prediction  
🔹 Profitability-based product classification  
🔹 Integration into Power BI dashboard  

## 🧑‍💻 Author
**Name:** Milan  
MBA in Operations & Analytics  
GitHub Portfolio Project
