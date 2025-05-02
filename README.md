# churn-prediction-telecom
Binary classification telecom customer churn

This project focuses on predicting customer churn for a telecom company.  
The goal is to identify which users are most likely to leave, so the company can take proactive retention measures.  
The operator's team provided data on concluded contracts, personal data and information on services provided: four small databases with sizes of up to 10 thousand records and with a number of features up to 8.

## 🎯 Objectives
- Predict the probability of customer churn using machine learning models
- Identify key factors that influence churn
- Provide actionable business recommendations

## 📂 Data Description
The dataset includes:
- Personal data (age, gender, dependents, etc.)
- Contract information (type of internet service, tenure, payment method)
- 'begin','end','payed_years','e_billing','payment_method','month_charges','total_charges'
- Service usage details (online security, phone service, streaming, etc.)

## 🔧 Tools and Technologies
- Python: pandas, numpy, matplotlib, seaborn
- Machine Learning: CatBoost, XGBoost, LightGBM
- Jupyter Notebook
- Metrics: ROC AUC, F1-score, Confusion Matrix
- Feature importance analysis

## 🧪 Project Workflow
1. Data cleaning and preprocessing
2. Exploratory data analysis (EDA)
3. Feature engineering and encoding
4. Model training (boosting algorithms)
5. Evaluation and comparison of models
6. Interpretation of results and business recommendations

## 📈 Key Results
- Final model AUC: **0.87**
- Important features: contract type, internet service, technical support, tenure
- Suggested retention strategies for high-risk customer segments

## 📝 Business Recommendations
- Target customers with short tenure and monthly contracts with loyalty offers
- Improve customer support for users using multiple services
- Monitor contract types that correlate with higher churn risk

## 📊 Visualizations
![Churn Distribution](images/churn_distribution.png)  
![Feature Importance](images/feature_importance.png)
