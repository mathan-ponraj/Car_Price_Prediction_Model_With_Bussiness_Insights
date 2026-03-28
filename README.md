# Automotive Pricing Intelligence and Sales Optimization

## Project Overview
This project is a data-driven pricing system designed for the used car market. I built an end-to-end analytics workflow that replaces manual guesswork with machine learning and business intelligence. The system predicts optimal selling prices and provides a dashboard for managers to make faster, more profitable decisions.

## The Business Problem
Used car dealers often struggle with inconsistent pricing. If a car is priced too high, it sits in the lot for months; if it is priced too low, the company loses money. This project solves that by creating a standardized pricing engine based on historical sales data.

## My Technical Workflow

1. Data Automation Pipeline: I built a Scikit-Learn pipeline to automate data cleaning, scaling, and encoding. This makes the system reproducible and ready for real-world data.
2. Exploratory Data Analysis (EDA): I analyzed how factors like vehicle age, fuel type, and transmission impact resale value. For example, I found that automatic cars generally hold a higher resale value in the current market.
3. Feature Engineering: I calculated the "Car Age" from the manufacturing year and removed non-essential data to improve model focus.
4. Predictive Modeling: I used Linear Regression to create a baseline pricing model. It achieved an R² Score of 0.85, meaning it accurately explains 85% of the price variations.
5. Decision Intelligence: I created a simple framework that compares the predicted price against the current dealer price to flag if a car is "Overpriced" or "Underpriced."

## Business Impact & KPIs
Beyond just code, I defined key performance indicators (KPIs) to measure success:
- Inventory Turnover: Reducing the time a car stays unsold.
- Price Accuracy: Minimizing the gap between predicted and actual sales price.
- Profit Margin: Identifying undervalued cars to increase returns.

## Tools and Technologies
- Data Processing: Python (Pandas, NumPy)
- Machine Learning: Scikit-learn (Pipelines, Linear Regression)
- Visualization: Matplotlib, Seaborn
- Business Intelligence: Power BI (for stakeholder dashboards)

## Future Goals
To further optimize this intelligence system, I plan to:
- Implement XGBoost or Random Forest to capture more complex pricing patterns.
- Integrate real-time market data through APIs.
- Build a web-based interface using Streamlit for instant pricing lookups.

---
Developed by Mathan Ponraj
CSE Graduate | Data Science and Analytics
[LinkedIn Profile](https://www.linkedin.com)
