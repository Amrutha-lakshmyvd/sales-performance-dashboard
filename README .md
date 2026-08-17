# Sales Performance Dashboard

**Kinetrexa Software Pvt. Ltd. — Data Analytics Internship (Task 1)**

## Overview

This project analyzes a real-world sales dataset to identify revenue trends, top-performing products, customer purchasing behavior, and regional sales performance, presented through an interactive dashboard.

## Dataset

* **Source:** Online Retail II Dataset (Kaggle / UCI Machine Learning Repository)
* **Description:** Transaction-level data from a UK-based online retailer, including invoices, products, quantities, prices, customers, and countries (Dec 2009 – Dec 2011).

## Tools Used

* Python (pandas, matplotlib, seaborn) — data cleaning \& exploratory analysis
* Google Colab — notebook environment
* Tableau Public — interactive dashboard
* ReportLab — business insights report

## Project Structure

```
sales-performance-dashboard/
├── data/
│   ├── raw/                 # original dataset
│   └── cleaned/              # sales\_cleaned.csv
├── notebooks/
│   └── Task1\_Sales\_Analysis.ipynb
├── dashboard/
│   └── (Tableau workbook or link to published dashboard)
├── reports/
│   └── Business\_Insights\_Report.pdf
└── README.md
```

## How to Reproduce

1. Open `notebooks/Task1\_Sales\_Analysis.ipynb` in Google Colab
2. Upload the raw dataset when prompted
3. Run all cells in order to reproduce the cleaning, KPIs, and charts
4. Cleaned data exports as `sales\_cleaned.csv`
5. Import `sales\_cleaned.csv` into Tableau Public to rebuild the dashboard

## Dashboard

**Live URL:** *https://public.tableau.com/app/profile/amrutha.lakshmy.vd/viz/SalesPerformanceDashboard\_17869546372480/SalesPerformanceDashboard?publish=yes*



## Core KPIs

|Metric|Value|
|-|-|
|Total Revenue|£20,476,260.45|
|Total Orders|40,077|
|Total Unique Customers|5,878|
|Average Order Value|£510.92|

## Key Insights

* Revenue is strongly seasonal, peaking each November ahead of the holiday season (\~£1.45M in Nov 2010, rising further into Nov/Dec 2011), against a baseline of £0.6M–£0.85M/month the rest of the year.
* Decorative and gift-oriented products are the strongest physical-product performers — the Regency Cakestand 3 Tier (£330,590) and White Hanging Heart T-Light Holder (£260,990) lead the list.
* The UK contributes \~85% of total revenue (£17.41M of £20.48M); EIRE (Ireland) is the largest international market at just 3.2% (£658,767), followed by the Netherlands and Germany.
* With 5,878 customers placing 40,077 orders (\~6.8 orders/customer on average), repeat purchasing plays a substantial role in revenue — motivating the customer segmentation work in Task 2.

## Author

Amrutha Lakshmy V D

