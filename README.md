# gold-price-forecasting
ANALYSIS AND FORECASTING OF GOLD PRICE TRENDS USING MACHINE LEARNING AND TIME SERIES STATISTICAL TECHNIQUES with Suphanan Keawduang, Supagorn Ruennakarn, Thanawat Boriboonthanaruk,Sathundorn Saiaut and Chalermrat Nontapa

# 🥇 Monthly Gold Price Forecasting

## 📌 Project Overview
This repository contains a time series forecasting project aimed at predicting monthly gold prices. By leveraging both traditional statistical methods and modern deep learning algorithms, this project explores the most effective approaches for capturing trends and patterns in financial time series data.

## 📊 Dataset
- **Frequency:** Monthly Data
- **Source:** Yahoo Financeช
- **Time Period:** start='2023-01-01', end='2026-02-25'
- **Target Variable:**  Closing Price (USD/oz)

## 🧠 Models Implemented
This project evaluates and compares multiple forecasting models:
1. **ARIMA (AutoRegressive Integrated Moving Average):** A classical statistical model used as a baseline for capturing linear dependencies.
2. **LSTM (Long Short-Term Memory):** A specialized Recurrent Neural Network (RNN) architecture designed to learn long-term sequences and non-linear patterns.
3. **Chronos:** A pre-trained foundation model for time series forecasting, utilized to benchmark against traditional and deep learning approaches.
4. **XGBoost** an optimized gradient boosting algorithm developed by Tianqi Chen for scalable and high-performance machine learning.

## 📂 Repository Structure
```text
gold-price-forecasting/
├── final_data.csv
├── Chornos.ipynb
├── XGboost_gold_6_ตัวแปร.ipynb
└── README.md

## 📈 Results & Evaluation

In this study, we evaluated four modeling approaches for gold price prediction. Performance metrics used for evaluation include **MAPE (Mean Absolute Percentage Error)**, **RMSE (Root Mean Squared Error)**, **MAE (Mean Absolute Error)**, and **Direction Accuracy**.

| Model | MAPE (%) | RMSE | MAE | Direction Accuracy (%) |
| :--- | :--- | :--- | :--- | :--- |
| **XGBoost** | **0.83** | **43.93** | **24.92** | 61.76 |
| ARIMA-ElasticNet | 1.28 | 79.23 | 39.47 | **65.06** |
| Chronos | 2.03 | 147.40 | 99.67 | 37.83 |
| LSTM | 2.63 | 135.45 | 81.39 | 54.52 |

### 🏆 Conclusion
Based on the evaluation using the test set, the **XGBoost** model achieved the best overall performance with the lowest MAPE value of **0.83%**, indicating the highest prediction accuracy among all tested models. 

These results suggest that the gradient boosting framework of XGBoost is highly effective at capturing the complex, non-linear patterns and volatility inherent in gold price data. Therefore, XGBoost is identified as the most suitable model for gold price prediction in this study.
