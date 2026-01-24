# Car Price Prediction using Machine Learning

## Case Study

### Problem
Used car pricing is influenced by multiple factors such as vehicle age, mileage, fuel type, ownership history, and market price. Accurately predicting resale value is challenging but essential for dealers and customers.

### Context
This project builds a **machine learning regression system** to predict the **selling price of used cars** using structured tabular data and real-world features.

### Impact
- Built a robust regression pipeline with **Random Forest**
- Achieved **R² score of 0.96**, indicating excellent predictive performance
- Delivered an interpretable model using **feature importance and SHAP**
- Enabled real-time price prediction for new car inputs

### Why It Matters
Accurate car price estimation helps:
- Sellers price vehicles competitively
- Buyers avoid overpaying
- Dealers optimize inventory valuation

---

## What I Did

- Performed **data cleaning and preprocessing**
- Engineered new features like **car age**
- Handled **outliers using IQR method**
- Conducted extensive **EDA and visualization**
- Built a **scikit-learn Pipeline** for preprocessing + modeling
- Trained and evaluated a **Random Forest Regressor**
- Explained model predictions using **SHAP values**
- Built an interactive **user input prediction system**

---

## How I Did It (STAR Method)

### Situation
The dataset contained numerical and categorical variables with outliers, skewed distributions, and mixed data types.

### Task
Develop a reliable and interpretable regression model to predict car selling prices with high accuracy.

### Action
- Cleaned dataset (duplicates, column normalization)
- Created `car_age` feature from manufacturing year
- Removed unnecessary columns (`car_name`, `year`)
- Detected and removed outliers using **Interquartile Range (IQR)**
- Performed Exploratory Data Analysis (EDA):
  - Price distributions
  - Feature correlations
  - Category-wise price comparisons
- Built preprocessing pipelines:
  - Numerical: imputation + scaling
  - Categorical: imputation + one-hot encoding
- Integrated preprocessing and model using **Pipeline + ColumnTransformer**
- Trained **RandomForestRegressor**
- Evaluated using:
  - R² Score
  - Mean Squared Error
- Explained predictions using:
  - Feature importance
  - SHAP summary, waterfall, and force plots

### Result
- **R² Score:** `0.958`
- Strong generalization on unseen test data
- Model predictions closely matched actual prices
- Clear understanding of key price-driving features

---

## Tech Stack

- **Programming Language:** Python
- **Data Analysis:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn
- **Model:** Random Forest Regressor
- **Preprocessing:** Pipeline, ColumnTransformer
- **Explainability:** SHAP
- **Evaluation Metrics:** R² Score, MSE

---

## Key Features Influencing Price

- Present Market Price
- Car Age
- Kilometers Driven
- Fuel Type
- Transmission Type
- Seller Type
- Ownership History

---

## Example Prediction

```text
Input:
- Present Price: 5.0 lakh
- KMs Driven: 34,342
- Fuel Type: Diesel
- Seller Type: Dealer
- Transmission: Automatic
- Owner: 1
- Car Age: 3

Output:
Predicted Selling Price: ₹3.39 lakh
```
