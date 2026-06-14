# Zepto Customer Rating Analysis

## Business Question
What causes poor customer ratings on Zepto, and how can it be improved?

## Overview
Analyzed 118,565 Zepto orders (from a 947K row quick-commerce dataset) to identify 
the key factors behind customer dissatisfaction. 31.53% of orders received 1-2 star ratings.

## Tools Used
- Python (Pandas, Matplotlib, Seaborn) — data cleaning & analysis
- Power BI — interactive dashboard
- Jupyter Notebook

## Key Findings
1. **31.53%** of Zepto orders received bad ratings (1-2 stars)
2. Delivery time, payment method, product category, distance, and 
   delivery partner rating showed **no significant difference** between 
   good and bad rated orders
3. **City is the major driver**: Hyderabad had a 45.71% bad rating rate vs 
   Bengaluru's 20.67% — a 25-point gap

## Recommendation
Zepto should urgently audit Hyderabad operations (delivery partners, 
warehouse processes) and replicate Bengaluru's operational model there. 
This could reduce bad ratings by an estimated 8,000 orders/month.

## Dashboard

<img width="1776" height="862" alt="zepto_dashboard png" src="https://github.com/user-attachments/assets/bf9b8502-4f92-4f54-ab93-6c3a577600ba" />


## Files
- `Zepto_Analysis.ipynb` — Full analysis notebook
- `Zepto_Customer_Rating_Analysis.pbix` — Power BI dashboard
- `zepto_dashboard.png` — Dashboard screenshot
- `city_bad_rating.csv`, `city_avg_rating.csv`, `rating_distribution.csv` — Summary data for Power BI
