# Project Background
This project analyses a fictional company using a simulated dataset.

CoreCircuit is an e-commerce company established in 2018 that sells consumer electronics through their website and mobile app. Although the company has generated over $28 million dollars in sales revenue since its inception, it has yet to fully leverage its data to drive decision-making. Thus, an analysis was conducted to evaluate their performance from 2019 to 2022.

The key insights and recommendations are provided on the following areas:
- **Sales Trend Analysis:** Evaluation of revenue over the period, focusing on Revenue, Volume and Average Order Value (AOV).
- **Product Performance:** Analysis of CoreCircuit's product line and product refunds.
- **Loyalty Program:** Evaluation on the impact of loyalty program on customer revenue generation.
- **Regional:** Evaluation of regional revenue and product performance.

# Data Structure
This conceptual model illustrates how the dataset could be normalized into multiple related tables.

![CoreCircuit ERD](https://github.com/jonathanchoo134/CoreCircuit-Analysis/blob/a74bd21eaebc74f9f19bba4c98314aa2322ace97/Figures/CoreCircuit_ERD.png)

# Executive Summary
After revenue peaked in the pandemic era, the company's revenue have experienced a continued decline. Key performance indicators have revealed year-over-year decreases: order volume by 40%, revenue by 46% and AOV by 10%. While this decline in performance might be attributed by the gradual recovery of the pandemic, the following analysis will explore the various contributing factors and highlight actionable insights for improvement.

Figures shown subsequently are taken from the Tableau dashboard. For the full interactive dashboard, please click this [link](https://public.tableau.com/shared/ZBK7MHK55?:display_count=n&:origin=viz_share_link). Below is a snapshot of the overview dashboard.

![Overview Snapshot](https://github.com/jonathanchoo134/CoreCircuit-Analysis/blob/b843c80a3fe19afae253492080d6638557a6cb3f/Figures/Executive%20Summary%201.png)

# Insights Deep-dive
## Sales Trend Analysis
![Sales](https://github.com/jonathanchoo134/CoreCircuit-Analysis/blob/570447de46bf1604e6696a06b113e7daee03da8d/Figures/Sales%201.png)

- From February 2021 to December 2022, AOV declined on a year-over-year basis for almost 23 consecutive months, with the exception on September 2022 where it increased 3.55%. On a month-over-month basis, AOV fluctuates between positive and negative. This suggests that despite intermittent MoM improvements, seasonality effects and other effects were insufficient to offset a sustained structural decline in transaction value.
- AOV decline served as an early indicator of broader business weakness, preceding the sustained year-over-year declines in revenue (21 consecutive months) and order volume (12 consecutive months).

## Product Performance

- Across the quarters, revenue is highly concentrated, with the top two products (27in 4K gaming monitor, Apple Airpods Headphones) contributing around 50–70% of total revenue, and the top four products (top two products plus Macbook Air Laptop and Thinkpad Laptop) accounting for more than 90% of total revenue. This indicates a strong dependency on top products and a decline in their performance could greatly affect revenue.
- Among the rest of the products, the Bose Soundsport Headphones and Apple Iphone were the worst performing products, contributing to around 0.02% and less than 1% of total revenue respectively.
