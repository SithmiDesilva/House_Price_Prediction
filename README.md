# 🏡 House Price Prediction using Linear Regression

[![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Made With](https://img.shields.io/badge/Made%20With-Scikit--Learn-orange)](https://scikit-learn.org/)
[![Status](https://img.shields.io/badge/Status-Complete-success)]()

> This project predicts the **median value of owner-occupied homes** using the **Boston Housing Dataset**. It performs extensive data exploration, preprocessing, and builds a **Linear Regression model** to understand the impact of various features on housing prices.

---

## 📁 Project Structure

📦 House-Price-Prediction
    -├── house_price_prediction_.py
    -├── README.md
    -├── requirements.txt
    -└── screenshots/
    -└── actual_vs_predicted.png

---

## 📊 Dataset Description

The dataset contains 506 observations with 14 attributes:

| Feature   | Description                                                        |
|-----------|--------------------------------------------------------------------|
| CRIM      | Per capita crime rate by town                                     |
| ZN        | Proportion of residential land zoned for large lots               |
| INDUS     | Proportion of non-retail business acres                           |
| CHAS      | Charles River dummy variable (1 if tract bounds river, 0 otherwise)|
| NOX       | Nitric oxides concentration                                       |
| RM        | Average number of rooms per dwelling                              |
| AGE       | Proportion of old owner-occupied units                            |
| DIS       | Weighted distances to employment centers                          |
| RAD       | Index of accessibility to radial highways                         |
| TAX       | Property-tax rate                                                 |
| PTRATIO   | Pupil-teacher ratio                                               |
| B         | Proportion of Black residents                                     |
| LSTAT     | % of lower status population                                      |
| MEDV      | Median home value (target variable)                               |

---

## ⚙️ Features

- ✅ Data loading and cleanup
- ✅ Outlier handling using Winsorization
- ✅ Exploratory Data Analysis (EDA) with Seaborn & Matplotlib
- ✅ Feature scaling using StandardScaler
- ✅ Model training with `LinearRegression`
- ✅ R² and MSE evaluation metrics
- ✅ Cross-validation (5-fold)
- ✅ User input-based prediction (CLI)

---

## 📈 Model Performance
 - Model: Linear Regression
 - R² Score (on test set): ~0.71–0.78 (depending on data split)
 - Cross-validated R²: Averaged over 5 folds
 - MSE: Varies based on train-test split, typically low

## 📉 Visualizations
 - Distribution plots for each feature
 - Correlation heatmap
 - Boxplots before and after outlier handling
 - Actual vs. Predicted scatter plot
 - Residual (error) distribution

## 🧠 Insights
 - RM (rooms per dwelling) positively influences house price.
 - LSTAT (lower status population) and CRIM have negative correlation with house price.
 - Residuals are fairly normally distributed, indicating model reliability.

## 📝 Future Improvements
 - Add other models like Random Forest or XGBoost for comparison.
 - Perform hyperparameter tuning.
 - Convert script into a web app using Streamlit or Flask.
 - Automate data collection and retraining pipeline









