# 📊 Delinquency Risk — Exploratory Data Analysis (EDA)

This repository contains the Exploratory Data Analysis (EDA) for the *Geldium Delinquency Prediction Project*, completed as part of the Tata iQ Analytics Simulation.  
The purpose of this project is to assess dataset quality, detect risk patterns, identify anomalies, and prepare the data for predictive modeling.

---

## 📁 Repository Contents
| File | Description |
 *eda_report_expanded.pdf* Extended EDA report including detailed insights, visuals, anomalies, risk indicators & recommendations |

---

## 🔍 Project Overview
Financial institutions rely heavily on delinquency prediction models to identify customers at risk of defaulting on payments.  
This EDA explores financial, behavioral, and historical data points to understand the early warning signals related to delinquency.

The analysis focuses on:
- Understanding dataset structure  
- Identifying missing values  
- Detecting data anomalies  
- Analyzing risk indicators  
- Visualizing key variables  
- Recommending data cleaning & preprocessing approaches  

---

## 📌 Key Insights from the EDA

### ✔ Missing Value Findings
- Income, Debt_to_Income_Ratio, and Credit_Utilization contain missing entries.  
- Recent payment history (Month_1 to Month_6) also has gaps.  
- Some Employment_Status entries are blank.

### ✔ Anomalies Detected
- Credit Utilization > 100% found in some rows — unrealistic and must be capped.  
- Potential extreme or noisy values in Income and Loan_Balance.  
- Payment history columns contain unexpected values beyond 0/1/2.

### ✔ Top Risk Indicators
Strong relationships with delinquency are observed for:
- *High Credit Utilization (%)*  
- *Missed Payments (Month_1–Month_6)*  
- *High Debt-to-Income Ratio*  
- *Low Credit Score*  
- *Employment Status: Unstable/Unemployed*  

These variables should be prioritized during feature engineering.

---

## 📈 Visual Insights Included
The EDA report includes visually rich charts for:
- Age distribution  
- Loan Balance distribution  
- Credit Utilization distribution  

These visuals help identify patterns, clusters & anomalies quickly.

---

## 🛠 Tools & Technologies
- *Python*
- *Pandas*
- *NumPy*
- *Matplotlib*
- *ReportLab* (for PDF generation)
- *GitHub*

---

## 🚀 Next Steps (Future Work)
- Perform feature engineering (risk flags, ratios, encodings)
- Build ML models like Logistic Regression, Random Forest, XGBoost  
- Evaluate using accuracy, F1, ROC-AUC  
- Test model fairness and bias  
- Deploy prediction pipeline  

---

## 👩‍💻Author
*Payal Mohokar*  
Delinquency Prediction — EDA Project  
Tata iQ Analytics Simulation

---

## 💬 Feedback & Contributions
Feel free to open issues or submit suggestions to improve this repository.
