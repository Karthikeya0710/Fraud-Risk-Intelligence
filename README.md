# 💳 Machine Learning-Based Financial Fraud Detection and Transaction Risk Analytics System

## 📌 Overview
This project presents a Machine Learning-Based Financial Fraud Detection and Transaction Risk Analytics System designed to identify potentially fraudulent transactions and generate explainable fraud risk assessments.

The system analyzes transaction characteristics such as transaction amount, spending behaviour, transaction velocity, geographical anomalies, payment channels, and location patterns to estimate fraud probability and classify transactions into:

- 🟢 Low Risk
- 🟡 Suspicious
- 🔴 High Risk Fraud

The project evaluates multiple machine learning algorithms, including Random Forest, LightGBM, and XGBoost, on a large-scale financial transaction dataset containing **5 million records**.

---

## 🎯 Objectives
- Detect potentially fraudulent financial transactions.
- Estimate fraud probability scores for transactions.
- Classify transactions into different risk categories.
- Generate explainable fraud analysis reports.
- Compare multiple machine learning algorithms for fraud detection.

---

## 📊 Dataset Information

| Attribute | Value |
|-----------|--------|
| Total Transactions | 5,000,000 |
| Original Features | 18 |
| Target Variable | is_fraud |
| Fraudulent Transactions | 179,553 |
| Non-Fraudulent Transactions | 4,820,447 |

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- LightGBM
- Jupyter Notebook

---

## ⚙️ Project Workflow

1. Data Collection
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing
4. Feature Engineering
5. Model Development
6. Model Evaluation
7. Fraud Probability Estimation
8. Fraud Analysis Simulator

---

## 🔍 Key Features
- Exploratory Data Analysis (EDA)
- Data Cleaning and Preprocessing
- Feature Engineering
- Fraud Pattern Analysis
- Random Forest Implementation
- LightGBM Implementation
- XGBoost Implementation
- Fraud Probability Estimation
- Explainable Fraud Analysis Simulator
- Risk Classification System

---

## 🤖 Machine Learning Models
- Random Forest
- LightGBM
- XGBoost

### Final Model Selected
🏆 **XGBoost**

Reason:
- Strong fraud probability estimation
- Excellent fraud detection capability
- High interpretability and explainability
- Suitable for early warning fraud detection systems

---

## 📈 Important Fraud Indicators
- Transaction Amount
- Spending Deviation Score
- Velocity Score
- Geographical Anomaly Score
- Time Since Last Transaction
- Transaction Location
- Payment Channel
- Merchant Category
- Device Used

---

## 🚨 Fraud Analysis Simulator

The developed simulator generates:

- Fraud Probability Score
- Risk Classification
- Decision Explanations
- Transaction Location Analysis
- Recommended Actions

### Risk Categories
🟢 Low Risk

🟡 Suspicious

🔴 High Risk Fraud

---

## 📂 Project Structure

```text
Financial-Fraud-Detection-and-Risk-Analytics-System
│
├── data
├── notebooks
│   ├── 01_EDA_Preprocessing.ipynb
│   ├── 02_XGBoost_Model.ipynb
│   ├── 03_Random_Forest_Model.ipynb
│   ├── 04_LightGBM_Model.ipynb
│   └── 05_Fraud_Analysis_Simulator.ipynb
│
├── images
├── docs
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 📊 Results Summary

| Model | Fraud Detection Capability | Fraud Probability Generation |
|-------|-----------------------------|------------------------------|
| Random Forest | Poor | Poor |
| LightGBM | Excellent | Good |
| XGBoost | Excellent | Excellent |

---

## 🚀 Future Enhancements
- Explainable AI (SHAP)
- Threshold Optimization
- Real-Time Fraud Monitoring
- Interactive Dashboard Development
- Cloud Deployment
- Integration with Banking Systems

---

## 👨‍💻 Author
**Karthikeya M**

Computer Science Engineering Student | Data Analytics & Machine Learning Enthusiast
