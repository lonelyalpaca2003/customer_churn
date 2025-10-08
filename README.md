# Bank Customer Churn Prediction

## Problem Statement

Customer churn is a critical challenge for banks - acquiring new customers costs significantly more than retaining existing ones. This project builds a machine learning model to predict which customers are likely to leave the bank, enabling proactive retention strategies.
Business Question: Can we identify at-risk customers before they churn and understand what drives their decision to leave?

## Dataset Overview
Source: Bank Customer Churn Dataset
Target Variable: Exited (1 = churned, 0 = retained)
Features:

Demographics: Age, Gender, Geography

Financial: CreditScore, Balance, EstimatedSalary

Banking Relationship: Tenure, NumOfProducts, IsActiveMember, HasCrCard

Customer Feedback: Complain, Satisfaction Score, Card Type, Points Earned


### Methodology
1. Data Preprocessing:

    Removed irrelevant features: RowNumber, CustomerId, Surname
    Encoded categorical variables
    Scaled numerical features

2. Models Evaluated

     Logistic Regression
     XGBoost


### How to Run

```bash
# Clone repository
git clone https://github.com/yourusername/bank-churn-prediction.git

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook
```
### Technologies Used

- Python 3.9+
- scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn
