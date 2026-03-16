# AutoValue ML

## Project Overview
The used car market is growing rapidly, but many dealers rely on guesswork for pricing vehicles. Incorrect pricing can lead to slow sales, unsold inventory, or direct revenue loss.  

This project builds a **machine learning workflow** to predict the selling price of used cars using historical sales data. It focuses on:  
- Structured **data preprocessing**  
- **Feature engineering**  
- **Predictive modeling**  
- **Business insights** to support dealer pricing decisions  

The goal is not only to predict prices but also to create a **reproducible, automated workflow** that reduces manual effort and improves model reliability.

---

## Business Problem
Used car dealers often face challenges in deciding the right selling price:  
- Vehicles priced too high remain unsold for longer  
- Underpriced vehicles lead to revenue loss  
- Manual analysis is time-consuming and inconsistent  
- Lack of structured data systems for pricing  

**Solution:** Use data-driven ML models and structured preprocessing to support consistent and informed pricing decisions.

---

## Key Highlights

### 1. Automated Data Preprocessing Workflow
- Built a **Scikit-Learn Pipeline** to automate data cleaning and transformation  
- Main tasks:
  - Handle numerical & categorical features  
  - Feature scaling  
  - Encoding categorical variables  
  - Preparing model-ready datasets  
- Benefits: **Improved reproducibility** and reduced manual cleaning effort  

### 2. Feature Engineering
- Created **Car_Age** from the manufacturing year  
- Removed non-informative columns like car names  
- Encoded categorical features for machine learning  
- Helped reduce noise and focus on relevant information  

### 3. Exploratory Data Analysis (EDA)
- Analyzed **price distribution**, correlation with vehicle attributes, and depreciation trends  
- Guided feature engineering and model design  

### 4. Predictive Modeling
- Implemented **Linear Regression** for price prediction  
- Advantages:
  - Easy to interpret for business users  
  - Understand how features influence price  
- Model trained on a **train-test split** and evaluated with standard metrics  

**Model Performance:**  
- R² Score: 0.85  
- MAE: 1.22  
- RMSE: 1.87  

---

## Business Impact
- Built a **predictive pricing model** for used vehicles  
- Automated data preprocessing via **Scikit-Learn pipeline**  
- Reduced dependency on guesswork  
- Enabled **faster and more consistent pricing analysis**  
- Estimated **15–20% reduction in profit loss** from incorrect pricing  

---

## Business Dashboard (Power BI)
Created a dashboard to make insights accessible for non-technical users:  
- Price trends by fuel type  
- Relationship between vehicle age and selling price  
- Transmission-wise price comparison  
- Overall pricing distribution  

---

## User Input Price Prediction
- Users can input:
  - Present price, kilometers driven, fuel type, transmission, number of owners, car age  
- Model predicts **estimated selling price**, supporting dealer-level decisions  

---

## Tools & Technologies
**Programming & Data Handling:** Python, Pandas, NumPy  
**Machine Learning:** Scikit-learn, Linear Regression, Pipeline, Feature Engineering  
**Data Visualization:** Matplotlib, Seaborn  
**Business Intelligence:** Power BI  
**Data Source:** CSV dataset of used vehicle sales  

---

## Skills Demonstrated
- Data cleaning & preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature engineering  
- Machine learning model development & evaluation  
- Scikit-Learn preprocessing pipelines  
- Translating model outputs into **business insights**  
- Analytical thinking for **real-world business problems**

---

## Conclusion
This project demonstrates how **structured data preprocessing, feature engineering, and machine learning** can solve a real-world pricing problem. It shows how ML can support **informed pricing strategies** in the growing used vehicle market.
