# PRCP-1000: Portuguese Bank Marketing Capstone Project

## 📌 Project Overview
This project is based on the **Portuguese Bank Marketing Dataset**, where direct phone call campaigns were conducted between **May 2008 – November 2010** to promote **term deposits** among existing customers.  

The main objective is to:
1. **Perform complete Exploratory Data Analysis (EDA)**  
2. **Build predictive models** to identify customers who are more likely to subscribe to a term deposit.  
3. **Provide actionable suggestions** to the marketing team for better targeting strategies.  

---

## 📊 Dataset Information
- **Source:** [Portuguese Bank Marketing Dataset](https://d3ilbtxij3aepc.cloudfront.net/projects/CDS-Capstone-Projects/PRCP-1000-ProtugeseBank.zip)  
- **File Used:** `Data > bank-additional > bank-additional-full.csv`  
- **Domain:** Finance / Banking  
- **Rows:** ~41,000  
- **Columns:** 20 input variables + 1 output variable  

### Target Variable:
- **y** → Client subscribed a term deposit? (`yes` / `no`)

---

## 🧾 Tasks Completed
### Task 1 – Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing  
- Univariate & bivariate analysis  
- Visualization of categorical and numerical features  
- Correlation study with social/economic context variables  

### Task 2 – Predictive Modeling
- Applied multiple ML models:  
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  
  - XGBoost / LightGBM  
- Compared model performance using **Accuracy, Precision, Recall, F1-Score, ROC-AUC**  
- Selected the **best model** for production deployment  

### Task 3 – Business Suggestions
- Key insights for improving marketing strategy:  
  - Targeting by job type, marital status, and education  
  - Importance of last campaign outcomes  
  - Best performing months/days for campaign success  
  - Suggestions for reducing unnecessary calls  

---

## 📈 Model Comparison Report
| Model               | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|----------------------|----------|-----------|--------|----------|---------|
| Logistic Regression  | xx%      | xx%       | xx%    | xx%      | xx%     |
| Decision Tree        | xx%      | xx%       | xx%    | xx%      | xx%     |
| Random Forest        | xx%      | xx%       | xx%    | xx%      | xx%     |
| XGBoost / LightGBM   | xx%      | xx%       | xx%    | xx%      | xx%     |

*(Fill actual results after running models)*  

---

## 🚀 Challenges & Solutions
- **Imbalanced Data:** Most customers do not subscribe → applied **SMOTE / class weights**  
- **High cardinality categorical features:** Encoded using **One-Hot Encoding**  
- **Duration variable issue:** Excluded from predictive modeling since it leaks target information  
- **Overfitting risk:** Controlled using **cross-validation, hyperparameter tuning, and regularization**  

---

## 📂 Project Structure
