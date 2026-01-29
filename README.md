# Car Price Prediction using Machine Learning

## Project Overview
This project is a **learning-focused regression analysis task** where I built a machine learning model to predict the **selling price of used cars** using structured tabular data.

The goal of this project was to practice the **complete machine learning workflow**, including data cleaning, feature engineering, model training, evaluation, and basic model interpretation.

---

## Problem Statement
Given vehicle-related features such as age, mileage, fuel type, transmission, and ownership history, the task is to predict the resale price of used cars.

---

## What I Worked On

- Cleaned and prepared a real-world used car dataset
- Performed exploratory data analysis (EDA) to understand feature relationships
- Created new features such as **car age**
- Handled outliers using the **IQR method**
- Encoded categorical variables and scaled numerical features
- Trained a **Random Forest Regressor**
- Evaluated model performance using regression metrics
- Interpreted model behavior using feature importance and SHAP

---

## Dataset Information
- Data Type: Tabular (numerical and categorical features)
- Target Variable: Selling price of used cars
- Features: Vehicle age, mileage, fuel type, transmission, ownership, market price, etc.

---

## Model Performance
- **Test R² Score:** ~0.96  

The model was able to explain a large portion of the variance in car prices and performed well on unseen test data.

---

## Tools & Technologies Used
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- SHAP  
- Jupyter Notebook  

---

## Key Learnings
- Importance of data cleaning and feature engineering in regression problems
- Handling mixed data types using preprocessing pipelines
- Applying ensemble models like Random Forest for tabular data
- Evaluating regression models using R² and error metrics
- Using SHAP and feature importance to understand model predictions

---

## Future Improvements
- Try hyperparameter tuning to improve model stability
- Compare results with simpler regression models
- Evaluate performance using additional metrics such as MAE and RMSE
