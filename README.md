# Car Price Prediction Model with Business Insights – End-to-End ML Project

This project showcases an end-to-end machine learning workflow to predict car resale prices. It includes data preprocessing, model training, model explainability using SHAP, and business reporting through a Power BI dashboard.

---

## Project Overview

The objective is to build a predictive model that estimates car prices based on various factors such as age, fuel type, seller type, and more. The workflow integrates machine learning with business insights to deliver a practical solution for understanding pricing trends in the resale car market.

---

## Features

- **ETL & Preprocessing Pipeline**  
  - Cleaned a dataset of 1,500+ car records by handling missing values and duplicates.
  - Removed outliers using IQR method and z-score detection.
  - Scaled numerical features with `StandardScaler`.
  - Encoded categorical features using `OneHotEncoder` integrated in a `ColumnTransformer`.

- **Model Building & Evaluation**  
  - Trained a `RandomForestRegressor` model achieving an R² score of **0.98** on training data and **0.95** on test data.
  - Hyperparameter tuning performed using GridSearchCV to optimise model performance.

- **Explainable ML (XAI)**  
  - Applied SHAP to interpret feature importance and visualise individual prediction breakdowns.
  - Identified that **Age**, **Fuel Type**, and **Seller Type** are the top 3 influencing factors on resale price predictions.

- **Exploratory Data Analysis (EDA)**  
  - Conducted statistical summaries and correlation analysis.
  - Created interactive distribution plots and trend lines to analyse the relationship between features and price.

- **Power BI Dashboard**  
  - Designed a dynamic dashboard displaying:
    - Average price segmented by Fuel Type.
    - Seller Type comparison insights showing dealer prices are on average **20% higher** than individual sellers.
    - Car Age vs Price trend analysis revealing a **12% price depreciation per year**.
  - Delivered the final dashboard in PDF format for business reporting.

---

## Technologies Used

- Python  
- Pandas, NumPy  
- Scikit-learn (Pipeline, ColumnTransformer, RandomForest)  
- SHAP (Explainable AI)  
- Matplotlib, Seaborn  
- Power BI

---

## Project Structure
```
Car_Price_Prediction_Model
├── README.md # Project documentation
├── car_data.csv # Raw dataset
├── cleaned_car_data.csv # Cleaned dataset post preprocessing
├── notebook/
│ └── Car_Price_Prediction.ipynb # Jupyter Notebook with complete workflow
├── car_price_insights_report.pdf # Power BI Dashboard report
├── requirements.txt # Required Python libraries
```

---

## Results

- Achieved an R² score of **95%** on test data, indicating strong predictive accuracy.
- Identified Age as the most influential factor, accounting for **40% variance** in price prediction.
- Business insights revealed that cars aged above 5 years depreciate by **60% of their original value**.
- Delivered a Power BI dashboard enabling stakeholders to analyse pricing trends and make informed pricing decisions.

---

## Conclusion

This project demonstrates the integration of machine learning models with business intelligence tools to create a comprehensive car price prediction and analysis system. By achieving **95% prediction accuracy** and uncovering key business insights, the model provides a practical and explainable solution for the automobile resale market, aiding data-driven decision-making.

---
