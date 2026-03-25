# Automotive Pricing Intelligence and Sales Optimization using Data Analytics

## Executive Summary
This project develops a data-driven pricing intelligence system for the used car market using data analytics, machine learning, and business intelligence dashboards. The objective is to replace manual and inconsistent pricing decisions with a structured analytics workflow that improves pricing accuracy, reduces unsold inventory, and supports profit-maximizing decisions.

The project combines data preprocessing automation, exploratory data analysis, predictive modeling, and business dashboards to convert raw vehicle data into actionable pricing insights and decision support tools.

---

## Project Overview
The used car market is growing rapidly, and guesswork in vehicle pricing directly affects revenue and sales performance. Incorrect pricing can lead to slow sales, unsold inventory, or revenue loss.

This project builds a Business-Driven Pricing Engine to predict the optimal selling price of used cars using historical sales data. The project focuses on:

- Structured data preprocessing  
- Feature engineering  
- Exploratory data analysis  
- Predictive modeling  
- Business insights and dashboards  
- Pricing decision support system  

The goal is not only to predict prices but also to create a reproducible analytics workflow that reduces manual effort and improves decision-making.

---

## Business Problem
Used car dealers often face challenges in deciding the right selling price:

- Vehicles priced too high remain unsold for longer  
- Underpriced vehicles lead to revenue loss  
- Manual analysis is time-consuming and inconsistent  
- Lack of structured data systems for pricing decisions  
- No standardized pricing strategy across inventory  

### Solution
Use data analytics and machine learning models to build a pricing decision support system that recommends optimal selling prices based on vehicle attributes and historical sales data.

---

## Analytics Workflow

### 1. Data Collection and Understanding
- Historical used car sales dataset
- Identified target variable: Selling Price
- Identified important features:
  - Present Price
  - Kilometers Driven
  - Fuel Type
  - Transmission
  - Number of Owners
  - Manufacturing Year

---

### 2. Data Preprocessing (Automation Pipeline)
Built a Scikit-Learn Pipeline to automate data preprocessing:

**Steps included:**
- Handling numerical and categorical features
- Missing value handling
- Feature scaling
- Encoding categorical variables
- Preparing model-ready datasets

**Benefits:**
- Improved reproducibility
- Reduced manual data cleaning
- Standardized preprocessing workflow
- Easier model deployment

---

### 3. Exploratory Data Analysis (EDA)
Performed exploratory data analysis to understand pricing patterns and relationships.

**Analysis performed:**
- Price distribution analysis
- Vehicle age vs selling price
- Fuel type vs price comparison
- Transmission vs price
- Correlation analysis
- Depreciation trend analysis

**Key Insights:**
- Selling price decreases significantly as vehicle age increases
- Automatic transmission cars generally have higher resale value
- Fuel type impacts resale price
- Large pricing variation exists for similar vehicles → pricing inefficiency

EDA helped guide feature engineering and model selection.

---

### 4. Feature Engineering
Created new features to improve model performance and interpretability:

- Created **Car_Age** from manufacturing year
- Removed non-informative columns like car names
- Encoded categorical variables
- Reduced noise in the dataset

Feature engineering improved model accuracy and business interpretability.

---

### 5. Predictive Modeling
Implemented Linear Regression for price prediction.

**Why Linear Regression?**
- Easy to interpret
- Explains feature impact on price
- Suitable for business decision-making
- Baseline model for pricing prediction

**Model Evaluation Metrics:**
- R² Score: 0.85
- Mean Absolute Error (MAE): 1.22
- Root Mean Squared Error (RMSE): 1.87

The model provides reliable price estimates for decision support.

---

## Decision Intelligence Layer
This project goes beyond prediction and focuses on pricing decision support.

### Pricing Decision Framework
The system compares:
- Predicted Price (Model Output)
- Current Market Price / Dealer Price

**Decision Rules:**
- If Predicted Price > Current Price → Vehicle is underpriced → Increase price
- If Predicted Price < Current Price → Vehicle is overpriced → Reduce price
- If both are similar → Price is optimal

This converts analytics into actionable pricing decisions.

---

## Business KPIs Defined
To measure business impact, the following KPIs were defined:

- Price Accuracy Percentage
- Inventory Turnover Time
- Profit Margin per Vehicle
- Unsold Inventory Rate
- Price Deviation (Actual vs Predicted Price)
- Average Days to Sell Vehicle

These KPIs help measure the effectiveness of the pricing strategy.

---

## Business Dashboard (Power BI)
A Power BI dashboard was created to make insights accessible to non-technical stakeholders.

**Dashboard Insights:**
- Price trends by fuel type
- Vehicle age vs selling price
- Transmission-wise price comparison
- Price distribution
- Depreciation analysis
- KPI tracking dashboard

**Business Value:**
- Converts analysis into decision-ready insights
- Helps managers make pricing decisions quickly
- Improves communication between analytics and business teams

---

## User Input Price Prediction System
A simple prediction interface was created where users can input:

- Present price
- Kilometers driven
- Fuel type
- Transmission
- Number of owners
- Car age

The system predicts the estimated selling price, helping dealers make pricing decisions for new inventory.

---

## Business Impact
This project creates a data-driven pricing system that improves decision-making in used car sales.

**Impact:**
- Standardized pricing strategy
- Reduced dependency on manual pricing
- Improved pricing consistency
- Faster pricing decisions
- Reduced unsold inventory
- Improved revenue optimization

**Estimated Business Impact:**
- 15–20% reduction in pricing errors
- Improved inventory turnover
- Increased profit margins through optimized pricing

---

## Tools & Technologies
**Programming & Data Processing**
- Python
- Pandas
- NumPy

**Machine Learning**
- Scikit-learn
- Linear Regression
- Pipeline
- Feature Engineering

**Data Visualization**
- Matplotlib
- Seaborn

**Business Intelligence**
- Power BI

**Data Source**
- Used car sales CSV dataset

---

## Skills Demonstrated
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Machine learning model development
- Model evaluation
- Scikit-Learn preprocessing pipelines
- Power BI dashboard development
- Business KPI definition
- Pricing analytics
- Translating data analysis into business decisions
- End-to-end data analytics project development

---

## Conclusion
This project demonstrates how data analytics, feature engineering, and machine learning can be used to solve a real-world pricing problem in the used car market. The project not only predicts vehicle prices but also builds a pricing decision support system with dashboards and KPIs, helping businesses make data-driven pricing decisions and improve revenue performance.

This project represents an end-to-end data analytics workflow from data preprocessing to business decision-making and dashboard reporting.
