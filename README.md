# Amazon-Sales-Analytics-Project
🛍️ Amazon Sales Analytics Project
📊 Project Overview

This project performs an end-to-end analysis of the Amazon Great Indian Festival sales performance across 2023 and 2024, and predicts the expected sales trend for 2025 using Python, Power BI, and Machine Learning.

The goal is to extract actionable insights on sales growth, category performance, customer trends, and the impact of discounts and advertisements — helping understand how festive campaigns influence e-commerce revenue.

🧠 Key Objectives

Data Generation & Cleaning:

Created a synthetic but realistic dataset of over 12,000 transactions for 2023–2024.

Cleaned missing values, handled duplicates, verified ranges for price, units, and discounts.

Feature Engineering:

Added time-based attributes: year, month, day, and is_festival_day.

Derived new metrics such as order value, average discount, and category-wise sales share.

Exploratory Data Analysis (EDA):

Visualized monthly revenue trends, category-wise units sold, and discount vs revenue impact using Matplotlib and Pandas.

Compared 2023 vs 2024 performance, identifying top-performing categories and regions during the Great Indian Festival month (October).

Power BI Dashboard:

Designed an interactive dashboard showing:

Yearly & monthly revenue KPIs.

Category and state-wise breakdowns.

Top-selling products and brands.

Average order value and discount correlation.

2025 forecast visualization.

Predictive Modeling (2025 Forecast):

Aggregated data to monthly level.

Trained Random Forest Regressor to forecast 2025 monthly revenue using features like discount, ad spend, units, and seasonality.

Achieved low mean absolute error on validation and visualized predicted growth curve.

⚙️ Tools & Technologies

Languages: Python (NumPy, Pandas, Matplotlib, Scikit-learn)

Visualization: Power BI

Machine Learning: Random Forest Regressor (for revenue forecasting)

Data Handling: CSV-based synthetic data (12k+ records)

📁 Dataset Files
File	Description
amazon_gif_sales_2023_2024.csv	Transaction-level sales data for 2023–2024
amazon_monthly_agg_2023_2024.csv	Aggregated monthly sales for modeling
amazon_gif_2025_monthly_predictions.csv	Forecasted monthly revenue for 2025
📈 Insights Derived

Revenue increased by ~15% YoY during the 2024 festival period.

Electronics and Fashion dominated festive sales.

Heavy discounts did not always lead to higher revenue — optimal discount range found around 10–20%.

2025 forecast predicts another 10–12% revenue growth assuming similar promo strategy.

🚀 Future Scope

Add customer segmentation and sentiment analysis using reviews.

Implement Prophet or SARIMA for category-level forecasting.

Deploy the dashboard with real-time data updates.
