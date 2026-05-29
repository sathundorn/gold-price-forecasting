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
├── data/
│   └── final_data.csv
├── notebooks/
│   ├── 01_XGboost_gold_6_ตัวแปร.ipynb
│   └── 02_Chronos.ipynb
├── requirements.txt
└── README.md
