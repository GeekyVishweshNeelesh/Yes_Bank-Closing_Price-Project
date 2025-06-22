# 📈 Stock Price Prediction of Yes Bank Using Supervised Machine Learning

This project involves building an end-to-end machine learning pipeline to **predict the monthly closing stock prices of Yes Bank**, leveraging historical market data and various regression-based models. The focus is on using **Linear Regression**, **Random Forest**, and **XGBoost Regressor** to forecast stock prices accurately, with the goal of supporting better financial decision-making.

---

## 🧠 Problem Statement

The objective is to develop a predictive model that can forecast the **monthly closing price** of Yes Bank using historical stock data (Open, High, Low, Close, and Volume). Accurate stock price prediction has real-world applications in trading, investment, and financial risk management. The challenge lies in selecting appropriate features, preprocessing data effectively, and choosing models that generalize well across different time periods.

---

## 📁 Project Type

**Supervised Machine Learning – Regression**

---

## 🚀 Features Implemented

- Exploratory Data Analysis (EDA)
- Data Preprocessing (missing values, outliers, encoding)
- Feature Engineering & Feature Selection
- Feature Scaling and Transformation
- Train/Test Split
- Model Building:
  - Linear Regression
  - Random Forest Regressor
  - XGBoost Regressor
- Model Evaluation:
  - MSE, MAE, R², Adjusted R²
- Hyperparameter Tuning using GridSearchCV
- Feature Importance & Model Explainability
- Saving & Loading Models (`joblib`)
- Sanity Check Predictions on Unseen Data

---

## 📊 Evaluation Metrics

| Metric | Linear Regression | Random Forest | XGBoost (Tuned) |
|--------|-------------------|----------------|------------------|
| MSE    | 113.96            | 201.61         | **211.26**       |
| MAE    | 6.50              | 8.85           | **9.45**         |
| R²     | 0.987             | 0.9777         | **0.9766**       |
| Adj. R²| 0.9854            | 0.9741         | **0.9729**       |

---

## 🔍 Final Model Chosen

**XGBoost Regressor (Tuned)** – selected for its ability to model complex, non-linear relationships and regularization capabilities that reduce overfitting.

---

## 📂 Repository Structure

├── data/
│ └── data_YesBank_StockPrices.csv
├── notebooks/
│ └── YesBank_Stock_Price_Prediction.ipynb
├── models/
│ └── best_xgb_model.joblib
├── README.md
└── requirements.txt

## 🛠️ Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn
- XGBoost
- Joblib / Pickle
- Jupyter Notebook

