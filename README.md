# 🚗 Car Price Prediction Model with Business Insights - End-to-End ML Project

This repository showcases a complete **end-to-end machine learning project** on predicting car resale prices. It includes data preprocessing, model building, explainable ML with SHAP, and a business-ready dashboard in Power BI.

**Pipeline + Explainable ML + Power BI Dashboard**
---

## 📌 Project Workflow

### 1. **ETL + Preprocessing Pipeline**
- Handled missing values using `SimpleImputer`
- Removed duplicates and handled outliers
- Used `StandardScaler` for numerical features
- Applied `OneHotEncoder` for categorical features
- Built a `ColumnTransformer` and full pipeline using `RandomForestRegressor`

### 2. **Model Training**
- Split data into train-test sets
- Fit the pipeline to the training data
- Evaluated using accuracy/R2 score (regression task)

### 3. **Explainable ML (XAI)**
- Used **SHAP** to explain global and local predictions
- Visualized feature importance
- Generated **SHAP waterfall plots** to show feature contributions

### 4. **EDA (Exploratory Data Analysis)**
- Summary statistics and correlation matrix
- Distribution plots (price, age, fuel type, etc.)
- Relationship analysis: Age vs Price, Fuel vs Price
- Visualized with `matplotlib` and `seaborn`

### 5. **Power BI Dashboard**
- Exported cleaned dataset
- Created KPI cards and charts:
  - Price distribution
  - Average price by fuel type
  - Seller type comparison
  - Car age trend line
- Final dashboard exported to PDF

---

## 📊 Tools & Technologies
- Python, Pandas, Numpy
- Scikit-learn (Pipeline, ColumnTransformer, RandomForest)
- SHAP (for model explainability)
- Seaborn & Matplotlib (for EDA)
- Power BI (for reporting)

---

## 📁 Files
- `car_data.csv` - raw dataset
- `notebook` - code work
- `cleaned_car_data.csv` - exported clean dataset
- `car_price_insights_report.pdf` - Power BI dashboard report

---


## ✅ Outcome

- Built a robust car price prediction model with explainability.
- Gained insights into factors that influence car pricing.
- Delivered a business-friendly dashboard using Power BI.

---


## 🤝 Let's Connect!
Open to Data Analyst / ML Intern opportunities.  
Connect with me:
- 📧 Email: [mathanponraj03@gmail.com]
- 💼 LinkedIn: [www.linkedin.com/in/mathan03]

---

### ⭐ Don't forget to star this repo if you liked the work!
# Car_Price_Prediction_Model_With_Bussiness_Insights
