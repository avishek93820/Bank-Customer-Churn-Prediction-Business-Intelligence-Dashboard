# 🏦 Bank Customer Churn Prediction & Business Intelligence Dashboard

> An end-to-end Data Analytics and Machine Learning project that predicts customer churn and transforms insights into an interactive Power BI dashboard for business decision-making.

![Python](https://img.shields.io/badge/Python-3.10-blue?style=flat-square&logo=python)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=flat-square&logo=powerbi)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=flat-square&logo=scikitlearn)


---

# 📌 Overview

Customer churn is one of the biggest challenges faced by banks. Retaining existing customers is significantly more cost-effective than acquiring new ones.

This project analyzes customer behavior, identifies key factors influencing churn, builds machine learning models to predict customer attrition, and presents actionable insights through an interactive Power BI dashboard.

The project demonstrates a complete data analytics workflow from raw data to business recommendations.

---

# 🎯 Business Problem

Banks need to identify customers who are at risk of leaving before they actually churn.

This project aims to:

- Analyze customer behavior
- Discover factors affecting churn
- Predict customer churn using Machine Learning
- Visualize business insights through Power BI
- Recommend strategies to improve customer retention

---

# 🛠️ Tech Stack

### Programming
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### Business Intelligence
- Microsoft Power BI

### Machine Learning Models
- Logistic Regression
- Random Forest Classifier

---

# 📂 Project Structure

```
Bank-Customer-Churn-Prediction/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_Data_Understanding.ipynb
│   ├── 02_EDA.ipynb
│   └── 03_Model_Training.ipynb
│
├── dashboard/
│   ├── Bank_Customer_Churn.pbix
│   └── screenshots/
│
├── images/
│
├── README.md
└── requirements.txt
```

---

# 📊 Dataset

The dataset contains customer banking information such as:

- Customer ID
- Age
- Gender
- Occupation
- Branch Code
- City
- Current Balance
- Previous Balance
- Monthly Credit
- Monthly Debit
- Churn Status

---

# ⚙️ Feature Engineering

The following features were created to improve predictive performance:

| Feature | Description |
|----------|-------------|
| Balance Change | Difference between current and previous balance |
| Credit Change | Difference between current and previous month's credit |
| Debit Change | Difference between current and previous month's debit |
| Total Transactions | Total monthly credits and debits |
| Balance Ratio | Ratio of current balance to previous balance |

These engineered features capture customer financial behavior more effectively than raw features.

---

# 📈 Exploratory Data Analysis

EDA was performed to understand customer behavior and identify churn patterns.

The analysis included:

- Customer demographics
- Churn distribution
- Balance analysis
- Credit and debit transaction analysis
- Branch-wise churn
- City-wise churn
- Correlation analysis

---

# 🤖 Machine Learning

Two classification models were developed:

| Model | Purpose |
|--------|---------|
| Logistic Regression | Baseline Model |
| Random Forest | Final Model |

### Model Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

Random Forest outperformed Logistic Regression and was selected as the final predictive model.

---

# 📊 Power BI Dashboard

An interactive three-page dashboard was developed to communicate business insights effectively.

## 📄 Page 1 – Executive Summary

**Visuals**

- KPI Cards
- Churn Rate
- Customer Distribution
- Gender Analysis
- Occupation Analysis
- Age Distribution

**Purpose**

Provide executives with a quick overview of customer churn.

---

## 📄 Page 2 – Customer Behavior Analysis

**Visuals**

- Average Current Balance by Customer Status
- Credit vs Debit Behavior
- Top 10 Cities by Churn
- Top 10 Branches by Churn
- Interactive Filters

**Purpose**

Analyze customer financial behavior and identify churn patterns.

---

## 📄 Page 3 – Machine Learning Insights

**Visuals**

- Model Performance KPIs
- Feature Importance
- Model Comparison
- ROC Curve
- Business Recommendations

**Purpose**

Translate machine learning results into actionable business insights.

---

# 🔑 Key Findings

- Customers with lower balances were more likely to churn.
- Financial behavior was a stronger predictor than demographic information.
- Balance Ratio emerged as the most influential feature.
- Certain branches and cities experienced higher churn rates.
- Random Forest achieved superior predictive performance.
- Early identification of high-risk customers enables proactive retention strategies.

---

# 💼 Business Recommendations

- Monitor customers with declining balance ratios.
- Launch personalized retention campaigns for high-risk customers.
- Focus relationship managers on customers with decreasing account activity.
- Prioritize branches and cities with higher churn rates.
- Deploy predictive analytics for early churn detection.

---

# 📸 Dashboard Preview

## Executive Summary

![Executive Summary](/Bank-Customer-Churn-Prediction/dashboard/Page-1.png)

## Customer Behavior Analysis

![Customer Behavior Analysis](/Bank-Customer-Churn-Prediction/dashboard/Page-2.png)

## Machine Learning Insights

![Machine Learning Insights](/Bank-Customer-Churn-Prediction/dashboard/Page-3.png)

---

# 🚀 Getting Started

## Clone the Repository

```bash
git clone https://github.com/yourusername/Bank-Customer-Churn-Prediction.git
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Run the Notebooks

Execute the notebooks in the following order:

1. `01_Data_Understanding.ipynb`
2. `02_EDA.ipynb`
3. `03_Model_Training.ipynb`

## Open the Dashboard

Open the Power BI dashboard:

```
dashboard/Bank_Customer_Churn.pbix
```

using Microsoft Power BI Desktop.

---

# 📚 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning
- Classification Models
- Model Evaluation
- Power BI Dashboard Development
- Data Visualization
- Business Intelligence
- Business Storytelling

---

# 🔮 Future Improvements

- Deploy the machine learning model using Streamlit or Flask.
- Integrate real-time banking transaction data.
- Automate dashboard refresh using Power BI Service.
- Experiment with XGBoost and LightGBM models.
- Perform customer segmentation for targeted marketing.

---

# 👨‍💻 Author

**Avishek Chatterjee**

- 💼 LinkedIn: https://linkedin.com/in/avishek-chatterjee6504
- 💻 GitHub: https://github.com/avishek93820

---

## ⭐ If you found this project helpful, consider giving it a star!

This project demonstrates an end-to-end workflow combining **Python, Machine Learning, and Power BI** to solve a real-world banking analytics problem and support data-driven decision-making.
