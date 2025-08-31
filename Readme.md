# 📌 Loan Approval Prediction

This project predicts whether a loan application will be **Approved** or **Rejected** based on applicant demographics, income, assets, and credit score.  

The project applies **machine learning models** (Random Forest and Logistic Regression) to analyze patterns and make predictions.

---
## 📂 Dataset

- **Rows:** 4,269  
- **Columns:** 13  
- **Target Variable:** `loan_status` (Approved / Rejected)  
---
## 🛠️ Tools & Libraries

This project was implemented in **Python** using:

- `pandas`, `numpy` → data manipulation  
- `matplotlib`, `seaborn`, `plotly` → visualizations  
- `scikit-learn` → preprocessing, modeling, evaluation  
- Models: `LogisticRegression`, `RandomForestClassifier`

---
## 🔎 Exploratory Data Analysis (EDA)

- **Class distribution**: Checked balance of Approved vs Rejected loans  
- **Boxplots & histograms**: Identified outliers and feature distributions  
- **Scatter plots**: Relationship between `income_annum` and `loan_amount`  
- **CIBIL score distribution**: Showed clear separation between approvals and rejections  

---

## ⚙️ Data Preprocessing

- Removed leading/trailing spaces from column names  
- **Label Encoding**: Applied to `loan_status` (target)  
- **One-Hot Encoding**: Applied to `education`, `self_employed`  
- **Scaling**: Applied to numerical features for better ML performance  

---

## 📊 Key Insights

- **CIBIL Score** is the most important factor in loan approval.  
- Higher **income** and **asset values** increase approval chances.  
- Random Forest provides excellent accuracy but Logistic Regression is useful for interpretability.  

---
