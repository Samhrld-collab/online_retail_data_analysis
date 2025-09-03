# BIT2053 – E-commerce Data Analysis Project

## 📖 Executive Summary
This project analyzes an e-commerce retail dataset to uncover insights on product sales, customer behavior, and geographic revenue distribution. Using BI tools, we created an interactive dashboard that helps businesses make data-driven decisions.

## ❓ Problem Statement
The online retail company lacked visibility into:
- Which products generate the highest revenue
- Which customers contribute the most to long-term growth
- Which geographic markets present expansion opportunities

## 📊 Dataset Source
- Dataset: [UCI Online Retail Dataset](https://archive.ics.uci.edu/dataset/502/online+retail+ii)  
- Transactions from **Dec 2009 – Dec 2011**  
- 1,048,575 records, 8 columns  

## 🔧 Methodology
1. Data Cleaning & Preprocessing
- Load and validate Online Retail II dataset
- Clean data: remove duplicates, handle missing values, filter invalid transactions
- Engineer features: calculate total amounts, extract time components
- Filter date range (2010-2011) for focused analysis
2. Exploratory Data Analysis
- Revenue Analysis: Calculate total revenue (£16.3M), order metrics, and KPIs
- Product Performance: Identify top-performing products by revenue and quantity
- Customer Behavior: Analyse purchase patterns and customer lifetime metrics
- Temporal Trends: Monthly/quarterly revenue patterns and seasonality
- Geographic Distribution: Country-wise performance analysis
3. Dashboard Creation in Google Looker Studio
- Recency: Days since last purchase from analysis date
- Frequency: Total unique transactions per customer
- Monetary: Total amount spent by customer
- Scoring: Quintile-based 1-5 scoring system for each RFM dimension
- Segmentation: 11 distinct customer segments (Champions, Loyal, At Risk, etc.)
4. Business Recommendations
- Champions (High R,F,M) → Reward & retain
- Loyal Customers → Upsell premium products  
- At Risk (Low R, High F,M) → Win-back campaigns
- New Customers → Onboarding & support
- Cannot Lose Them → Aggressive retention

## 📈 Results
- **Total Revenue:** £16,273,396.94  
- **Total Orders:** 34,945  
- **Average Order Value (AOV):** £465.69  
- **Unique Customers:** 5,771  
- **Unique Products:** 4,509  

**Top Products by Revenue:**
- Regency Cakestand 3 Tier (£273k)  
- White Hanging Heart T-Light Holder (£229k)  
- Jumbo Bag Red Retrospot (£133k)  

**Top Countries by Revenue:**
- United Kingdom (£13.4M)  
- EIRE (£592k)  
- Netherlands (£527k)  
- Germany (£408k)  
- France (£337k)

## 🖥 BI Dashboard (Google Looker Studio)
The [dashboard](https://lookerstudio.google.com/u/0/reporting/8c5247b9-81f9-4fbe-8b56-b465fec781c3/page/RlNWF) includes:
* Executive KPIs: Revenue, orders, customers, products
* Interactive Filters: Date range, country, product selection
* Customer Segments: RFM-based segmentation with actionable insights
* Geographic Analysis: Revenue distribution across markets
* Trend Analysis: Time-series revenue patterns

-----
![Online_Retail_Data_Visualisation (3)_page-0001](https://github.com/user-attachments/assets/93f9114c-2add-4bd0-9ef4-21a2058442b0)
-----

## ✅ Acknowledgement
- Dataset provided by UCI ML Repository  
- Course Intructor - Mr. Nazmirul Izzad Bin Nassir (City University | Lecturer)
