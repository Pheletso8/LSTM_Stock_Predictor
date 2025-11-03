# 📈 JSE Stock Price Prediction using LSTM & React Dashboard
## 🧠 Overview

This project builds an LSTM-based deep learning model to predict stock prices of JSE-listed companies (Johannesburg Stock Exchange) using historical data.
It includes a Python backend for data preprocessing, model training, and prediction, and an interactive ReactJS dashboard for visualizing model performance with tools such as date filtering, prediction comparison, and backtesting results.

The goal is to demonstrate full-stack data science capabilities — combining machine learning, time-series analysis, API integration, and front-end visualization — while exploring the feasibility of using LSTM networks in financial forecasting for South African markets.

## 🚀 Project Objectives

Collect and preprocess historical JSE stock data (daily closing prices, OHLC, etc.).

Build and train a Long Short-Term Memory (LSTM) model using Python (TensorFlow/Keras).

Evaluate the model using metrics like MAE, RMSE, and R².

Implement backtesting to assess predictive performance over different time periods.

Develop an interactive ReactJS dashboard to visualize:

Historical vs. Predicted stock prices

Model performance metrics

Backtesting results over selected date range


## ⚙️ Tech Stack
Backend (Python)

🐍 Python 3.x

🧮 TensorFlow / Keras – LSTM implementation

🧹 Pandas & NumPy – data cleaning and time-series preprocessing

📊 Matplotlib / Seaborn – exploratory data visualization

🌐 Flask / FastAPI – REST API for serving predictions

Frontend (ReactJS)

⚛️ React 18+

📈 Recharts / Victory / Nivo – interactive stock charts

📅 React Datepicker – date range filtering

⚡ Axios / Fetch API – communication with backend

📚 Dataset

Source: Yahoo Finance or other open JSE APIs

Example symbols: NPN.JO (Naspers), SOL.JO (Sasol), FSR.JO (FirstRand)

Features used: Date, Open, High, Low, Close, Volume

Data frequency: Daily

Example of fetching data using Python’s yfinance:

import yfinance as yf

data = yf.download("NPN.JO", start="2015-01-01", end="2025-01-01")
print(data.head())

## 🖥️ Frontend Features

🔍 Select Stock: Choose any JSE-listed stock (e.g., NPN.JO, SOL.JO)

📆 Date Range Filter: Focus on specific training or testing intervals

🧮 Backtest View: See how well the model performs historically

📊 Comparison Graphs: Overlay of actual vs. predicted prices

⚙️ Performance Summary: MAE, RMSE, and trend accuracy


## React Chart Preview

Blue Line → Actual Prices

Orange Line → LSTM Predictions

Shaded Area → Backtesting Range

## ⚖️ Limitations

Stock prices are highly volatile and affected by external macroeconomic factors.

LSTM models may overfit historical data and fail on unseen market conditions.

This project is for educational and portfolio purposes only, not financial advice.

## 💡 Motivation

Predicting stock prices is one of the most complex and intellectually rewarding challenges in data science.
This project demonstrates:

Advanced time-series forecasting with deep learning (LSTM)

End-to-end data pipeline development (data → model → visualization)

Full-stack integration between a Python API and ReactJS frontend

Applied machine learning within a South African context using JSE data

The ultimate goal is to showcase strong analytical thinking, coding proficiency, and the ability to turn data into actionable insights.


## 📈 Future Enhancements

Add sentiment analysis from financial news or Twitter data

Support multiple models (ARIMA, Prophet, GRU) for comparison

Include real-time predictions via live API

# 🧑‍💻 Author

## Pheletso Marumoloe
## 📍 South Africa
## 💼 Aspiring Data Scientist | Machine Learning & Full-Stack Developer
