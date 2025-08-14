# Predictive Analysis: Telecommunications' Company Customer Churn

## 📊 Telco Customer Churn Prediction
Predicting telecom customer churn using exploratory data analysis (EDA), preprocessing, and machine learning models.

## 📌 Overview
This project analyzes customer churn patterns in the telecommunications industry using the Telco Customer Churn dataset. It demonstrates a complete machine learning workflow — from EDA to model tuning — to identify customers likely to leave, enabling proactive retention strategies.

## 🚀 Features
- Exploratory Data Analysis (EDA): Identify churn patterns and correlations.
- Data Preprocessing: Handle missing values, encode categorical features, scale numeric data.
- Model Training: Logistic Regression, Random Forest, Gradient Boosting, and more.
- Model Comparison: Evaluate models with accuracy, precision, recall, and F1-score.
- Hyperparameter Tuning: Optimize model performance.
- Feature Engineering: Create and test additional features.

##  🗂 Project Structure
1. [telco-customer-churn.csv](https://github.com/Lubula/Customer-Churn-Prediction/blob/main/WA_Fn-UseC_-Telco-Customer-Churn.csv)
2. [01-data-exploration.ipynb](https://github.com/Lubula/Customer-Churn-Prediction/blob/main/01-data-exploration.ipynb)
3. [02-data-preprocessing.ipynb](https://github.com/Lubula/Customer-Churn-Prediction/blob/main/02-data-preprocessing.ipynb)
4. [03-model-building.ipynb](https://github.com/Lubula/Customer-Churn-Prediction/blob/main/03-model-building.ipynb)
5. [04-model-comparison.ipynb](https://github.com/Lubula/Customer-Churn-Prediction/blob/main/04-model-comparison.ipynb)
6. [05-hyperparameter-tuning-feature-engineering.ipyn](https://github.com/Lubula/Customer-Churn-Prediction/blob/main/05-hyperparameter-tuning-feature-engineering.ipynb)b
└── README.md

## 📊 Workflow
- Data Exploration
- Visualize churn trends and correlations.
- Detect patterns in contract types, tenure, and payment methods.
- Preprocessing
- Encode categorical variables.
- Normalize numerical features.
- Handle missing values.
- Model Building
- Train multiple classification algorithms.
- Evaluate with metrics and confusion matrices.
- Model Comparison
- Compare different classifiers to find the best performer.
- Hyperparameter Tuning
- Use GridSearchCV/RandomizedSearchCV to improve accuracy.
- Feature Engineering
- Create new derived variables to boost model performance.

## 📈 Results
| Model               | Accuracy | Precision | Recall | F1-score |
| ------------------- | -------- | --------- | ------ | -------- |
| Logistic Regression | 81%      | 79%       | 75%    | 77%      |
| Random Forest       | 85%      | 83%       | 80%    | 81%      |
| Gradient Boosting   | 86%      | 84%       | 81%    | 82%      |
