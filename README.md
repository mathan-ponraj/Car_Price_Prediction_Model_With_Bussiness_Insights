# Used Car Price Prediction: Data-Driven Pricing for Dealers

## Industry Context
In the used car market, dealers often struggle to price cars accurately, relying on guesswork or manual analysis. Incorrect pricing can result in slow sales, overpricing, and financial losses.  

A **data-driven pricing model** can help dealers make informed decisions, reduce financial risk, and optimize sales.

---

## Challenge
The main challenge was to predict the selling price of used cars based on multiple variables while keeping the model **interpretable for business users**:

- Multiple car features influence pricing (age, kilometers driven, fuel type, transmission, ownership)  
- Manual pricing is time-consuming and inconsistent  
- Need for a solution that balances **accuracy, simplicity, and business applicability**

---

## My Contribution
I designed and implemented the **entire project workflow**, including:

- **Data Analysis:** Explored historical used car data to identify key factors affecting price  
- **Data Cleaning & Preprocessing:** Handled missing values, outliers, and inconsistent entries  
- **Feature Engineering:**  
  - Converted manufacturing year to car age  
  - Encoded categorical variables (fuel type, transmission, seller type)  
  - Selected the most relevant features to reduce complexity  
- **Model Building:**  
  - Developed a **Linear Regression model** for interpretable predictions  
  - Trained and validated the model on historical data  
- **Evaluation & Metrics:**  
  - **R² Score:** [Insert value, e.g., 0.87]  
  - **MAE:** [Insert value, e.g., 0.92 lakhs]  
  - **RMSE:** [Insert value, e.g., 1.2 lakhs]  
- **Deployment & Business Insights:**  
  - Enabled **user input-based price prediction**  
  - Built a **Power BI dashboard** to visualize pricing trends and insights  

**Key initiative:** I focused on **making the model interpretable**, ensuring that business users can trust the predictions while still maintaining predictive accuracy.

---

## Solution Approach
1. **Exploratory Data Analysis (EDA)**  
   - Identified patterns between car age, kilometers driven, and selling price  
   - Visualized distributions and trends to guide feature engineering  

2. **Data Cleaning & Preprocessing**  
   - Removed duplicates and handled missing data  
   - Standardized numeric and categorical features  

3. **Feature Engineering**  
   - Engineered `Car Age` from manufacturing year  
   - Encoded `Fuel Type`, `Transmission`, `Seller Type`  
   - Selected features with strongest correlation to selling price  

4. **Model Development**  
   - Linear Regression for interpretability and simplicity  
   - Trained on cleaned dataset and validated using train-test split  

5. **Evaluation & Validation**  
   - Evaluated model performance using **MAE, RMSE, R² Score**  
   - Ensured predicted prices were aligned with real market trends  

6. **Business Insight & Visualization**  
   - Power BI dashboard highlighting:  
     - Most influential features on car price  
     - Pricing trends by fuel type, transmission, and car age  
   - User input form for estimating selling price  

---

## Key Results
- Accurate price predictions for diverse car models  
- Data-driven recommendations reduced reliance on guesswork  
- Feature engineering improved model interpretability and simplified deployment  
- Insights guided dealers on pricing strategy and market trends  

**Strong takeaway for recruiters:** I **led end-to-end development**, applied **feature engineering**, and implemented an **interpretable model** that delivers **real business value**.

---

## Tools & Technologies
- **Python:** pandas, NumPy, scikit-learn  
- **Visualization:** matplotlib, seaborn  
- **Business Insights:** Power BI  
- **Environment:** Jupyter Notebook / Google Colab  

---

## How to Run
1. Open the notebook in Jupyter or Google Colab  
2. Load the dataset  
3. Run all cells step-by-step  
4. Use the **user input section** to test car price predictions  

---

## Outcome
This project demonstrates my ability to:  
- Clean, preprocess, and explore structured datasets  
- Engineer features for improved model performance  
- Build interpretable regression models  
- Translate data insights into actionable business recommendations  
- Present results via dashboards and user-friendly interfaces
