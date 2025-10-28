# 📊 Marketing Campaign Performance Analysis (HNG)

This project analyzes marketing campaign data to uncover insights that improve ROI, optimize ad spend, and guide data-driven marketing strategies.


## 🧠 Project Overview
The dataset provided by HNG contains key marketing performance metrics such as **CTR, CPC, ROI, and Conversion Rate** across different channels like Social Media, Email, and Paid Search.

The goal of this project was to:
- Identify high- and low-performing campaigns
- Analyze channel effectiveness
- Detect outliers in CPC and ROI
- Recommend strategies to improve marketing performance


## 🧹 Data Cleaning
- Inspected and corrected column names and data types  
- Handled missing values and converted `Date` column to datetime  
- Created new calculated columns:
  ```python
  df['CTR'] = (df['Clicks'] / df['Impressions']) * 100

## 📈 Key Insights

1. Social Media and Email Marketing showed the highest CTR.

2. Paid Search had a higher CPC but better conversion rate.

3. Outliers indicated wasted ad spend in some campaigns.

4. ROI improved when budgets were reallocated to cost-effective channels.


## Recommendations

1. Increase spending on high-CTR, low-CPC channels

2. Reevaluate or stop low-ROI campaigns

3. Optimize targeting and creatives via A/B testing

4. Implement real-time tracking and budget adjustments
   
   

##  🧰 Tools Used

1. Python (Pandas, Matplotlib, Seaborn)

2. Microsoft Excel

3. Python (for visualization)

4. Jupyter Notebook
   

##  📎 Files

Marketing_Campaign_Report_HNG.pdf — Final project report

marketing_campaign_dataset.csv — Cleaned dataset

README.md — Project summary

## AUTHOR
AKOGWU MCDONALD IKECHUKWU - Data Analyst

https://mcdonald006.github.io/AnalysisByMc-Portfolio/#portfolio
