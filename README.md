# Customer Churn Prediction

A machine learning project that predicts whether a telecom customer will cancel their subscription, built using Logistic Regression in Python.

---

## Overview

Customer churn — when a customer stops using a service — is a major business problem. This project uses the [Telco Customer Churn dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) to build a classifier that identifies customers likely to churn, helping businesses take proactive action.

The project covers a full ML pipeline: data cleaning, encoding, feature scaling, model training, and evaluation with multiple metrics.

---

## Results

| Metric | Value |
|--------|-------|
| Algorithm | Logistic Regression |
| Training Samples | ~5,634 |
| Testing Samples | ~1,409 |
| Accuracy | 80% |
| ROC-AUC Score | 0.84 |


---

## Key Findings

- Customers on **month-to-month contracts** churn at a significantly higher rate than those on 1 or 2-year contracts
- **Tenure** is a strong predictor — customers who churn tend to leave within the first few months
- Higher **monthly charges** correlate with increased churn probability

---


## Project Structure

```
customer-churn-prediction/
│
├── WA_Fn-UseC_-Telco-Customer-Churn.csv   # Dataset (download from Kaggle)
├── customer_churn_prediction.ipynb         # Main Jupyter notebook                
└── README.md
```

---

## How to Run

**1. Clone the repository**
```bash
git clone https://github.com/your-username/customer-churn-prediction.git
cd customer-churn-prediction
```

**2. Install dependencies**
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

**3. Download the dataset**

Download `WA_Fn-UseC_-Telco-Customer-Churn.csv` from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) and place it in the project folder.

**4. Run the notebook**
```bash
jupyter notebook customer_churn_prediction.ipynb
```

---

## Concepts Covered

- Binary classification with Logistic Regression
- Label encoding and one-hot encoding for categorical features
- Feature scaling using StandardScaler
- Model evaluation — Accuracy, Precision, Recall, F1-Score, Confusion Matrix
- ROC-AUC score 

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data-green)
![NumPy](https://img.shields.io/badge/NumPy-Numeric-lightblue)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-red)

---

## Dataset

- **Source:** IBM Sample Dataset via Kaggle
- **Link:** https://www.kaggle.com/datasets/blastchar/telco-customer-churn
- **Records:** 7,043 customers
- **Features:** 21 columns including contract type, tenure, monthly charges, and services used

---

*Project by Hanmandla Sainath Reddy | B.Tech ECE, Mahindra University*
