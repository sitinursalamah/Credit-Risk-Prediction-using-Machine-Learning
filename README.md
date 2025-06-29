# 🏦 Credit Risk Prediction using Machine Learning

This project focuses on developing a machine learning pipeline to predict credit risk using borrower data. The goal is to assist financial institutions in identifying high-risk loan applicants to minimize default rates and optimize lending decisions.

---

## 🔍 Project Pipeline

### 📊 1. Data Understanding
- Performed initial inspection of the dataset.
- Checked for missing values and handled them accordingly.
- Identified and removed duplicate records.
- Analyzed variable types and data distributions.

### 🛠️ 2. Data Preparation (Part 1)
- Created the binary target variable `credit_risk` from loan status.
- Dropped irrelevant or leakage features.
- Fixed incorrect data types and handled null values.
- Ensured data consistency and completeness.

### 📈 3. Exploratory Data Analysis (EDA)
- Visualized categorical variables using bar and pie charts.
- Explored numerical distributions using histograms and boxplots.
- Checked feature correlations using a heatmap.
- Analyzed loan issuance trends over time using a line chart.

### ⚙️ 4. Data Preparation (Part 2)
- Performed feature engineering:
  - Removed multicollinear features using VIF analysis.
  - Applied label encoding for categorical variables.
- Handled imbalanced classes using SMOTE oversampling.
- Split the dataset into training and testing sets.
- Standardized numerical features with `StandardScaler`.

### 🤖 5. Modeling
Trained and evaluated 4 classification models:
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost (Gradient Boosting)

### 📊 6. Model Evaluation
Each model was evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- ROC AUC Score
- Confusion Matrix

**🏆 Best Model: XGBoost**
- Accuracy: **98.22%**
- Recall (High Risk): **99.9%**
- Lowest false negative rate and best AUC score.

---

## ✅ Conclusion
From the five classification models trained and evaluated, **XGBoost** achieved the highest performance. It successfully minimized misclassification, especially in detecting **high-risk borrowers**, making it the most reliable model for credit risk prediction in this project.

---

## 💡 Business Recommendations

### ✔️ Use XGBoost Model
Integrate the XGBoost model into the loan evaluation system to improve accuracy and consistency in credit scoring.

### ⚡ Automate Credit Evaluation
Enable real-time predictions and automate alerts for high-risk applicants to support timely decision-making and further verification.

### 📈 Monitor Loan Trends
Use model predictions to track loan approval patterns and credit behavior trends over time (monthly/quarterly).

### 🛡️ Develop Risk Mitigation Strategy
Combine current predictions with historical repayment behavior to optimize credit limits, interest rates, or collateral policies.

---

## 🧠 Skills Applied
- Data Cleaning & Preparation (`pandas`, `numpy`)
- EDA & Visualization (`matplotlib`, `seaborn`)
- Feature Engineering (encoding, scaling, multicollinearity handling)
- Model Building & Tuning (`scikit-learn`, `xgboost`)
- Evaluation Metrics & Interpretation
- Business Insight Generation & Communication

---

## 📩 Let's Connect!
Feel free to fork, explore, or reach out if you'd like to collaborate, discuss, or provide feedback!

