# 📈 Tesla Stock Price Prediction

![Tesla Logo](https://upload.wikimedia.org/wikipedia/commons/e/e8/Tesla_logo.png {width="150" height="150"})

This project presents a machine learning-based approach for predicting Tesla stock price movement direction using historical OHLC data. It combines exploratory data analysis (EDA), feature engineering, and classification models to make informed predictions.

---

## 🔍 Objective

To predict whether the Tesla stock price will **increase or decrease** the next day using statistical and machine learning models, including:
- Logistic Regression
- Support Vector Machine (SVM)
- XGBoost
- Decision Tree

---

## 🧰 Technologies Used

| Tool              | Purpose                             |
|-------------------|-------------------------------------|
| `Python`          | Core programming language           |
| `pandas`, `numpy` | Data manipulation and processing    |
| `matplotlib`, `seaborn` | Visualization and EDA        |
| `scikit-learn`    | Machine learning models and metrics |
| `xgboost`         | Gradient boosting classifier        |

---

## 📂 Dataset Overview

Historical stock price data including the following features:
- Open, High, Low, Close, Volume
- Derived time features (day, month, year)
- Engineered indicators for trading pattern analysis

---

## 📊 Exploratory Data Analysis

### Distribution of Features  
![Feature Distributions](https://drive.google.com/uc?id=YOUR_FEATURE_DIST_IMAGE_ID)

### Box Plots  
![Box Plots](https://drive.google.com/uc?id=YOUR_BOXPLOT_IMAGE_ID)

### Close Price Over Time  
![Close Trend](https://drive.google.com/uc?id=YOUR_CLOSE_PRICE_IMAGE_ID)

---

## 🛠️ Feature Engineering

Derived features include:
- `open-close`: Difference between opening and closing price
- `low-high`: Intraday volatility
- `is_quarter_end`: Boolean indicating end of financial quarter
- `target`: Binary label indicating if next day’s closing price is higher

📌 Target Variable:
```text
target = 1 → Price will increase the next day  
target = 0 → Price will decrease the next day
