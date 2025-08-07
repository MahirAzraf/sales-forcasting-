# 🛒 Walmart Sales Forecasting with XGBoost

This project forecasts Walmart's weekly sales using historical data and machine learning techniques, focusing on time series feature engineering, EDA, and XGBoost. It includes an interactive dashboard to visualize weekly, monthly, and yearly sales trends.

---

## 📊 Project Overview

Sales forecasting is a crucial part of retail strategy. This project uses the Walmart dataset from Kaggle to:
- Analyze sales trends 📈
- Engineer time-based features (lag, rolling averages)
- Train and evaluate an XGBoost regressor

---

## 🧰 Tools & Libraries

- **Python**
- **Pandas / Numpy** – data handling
- **Matplotlib / Seaborn – data visualization
- **Scikit-learn** – metrics, preprocessing
- **XGBoost** – sales forecasting model
- **Google Colab** – for development

---

## 📁 Dataset

- Source: [Kaggle Walmart Sales Dataset](https://www.kaggle.com/datasets)
- File: `Walmart Data Analysis and Forecasting.csv`
- Key columns: `Weekly_Sales`, `Date`, `Store`, `Holiday_Flag`, `Temperature`, `CPI`, `Unemployment`

---

## 🚀 Project Steps

1. **Data Collection**
   - Used a structured sales dataset with economic and holiday data.

2. **Data Preprocessing**
   - Converted date to datetime format
   - Extracted time features (year, month, week, etc.)
   - Created lag features & rolling averages

3. **EDA (Exploratory Data Analysis)**
   - Trend analysis
   - Correlation heatmaps
   - Outlier detection

4. **Feature Engineering**
   - Added time lags and rolling window means
   - Categorical encoding (if necessary)

5. **Train-Test Split**
   - Time-based split (not random)

6. **Model Training**
   - Model: `XGBoost Regressor`
   - Target: `Weekly_Sales`

7. **Evaluation**
   - Metrics: RMSE, R²
   - Final RMSE: ~123K
   - R² Score: 0.9467


---
