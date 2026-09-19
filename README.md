# Stock Price Forecasting with LSTM

A deep learning project focused on forecasting daily stock closing prices using **Long Short-Term Memory (LSTM)** networks.

The project uses historical data from **GOOGL (Alphabet Inc.)** and **INTC (Intel Corporation)** and evaluates how different LSTM configurations perform on time series forecasting.

## Project Description

The goal is to learn temporal patterns from historical closing prices and predict the next trading day's price. The data is processed chronologically to preserve the time-series structure, with the final year reserved for testing.

The forecasting process uses a **5-day sliding window** to generate input sequences and a **1-day forecasting horizon**.

## What I Did

- Explored and prepared historical stock price data
- Selected closing prices for univariate forecasting
- Split the data chronologically into training and testing sets
- Applied data scaling and sliding-window transformation
- Built a baseline **LSTM model with 50 units**
- Developed a modified LSTM architecture and adjusted training parameters
- Compared model performance using **RMSE, MAE, and MAPE**
- Visualized actual and predicted stock prices

## Dataset

- `GOOGL.csv` — Alphabet Inc.
- `INTC.csv` — Intel Corporation

The datasets contain historical daily stock market information, with the analysis focusing on the `Date` and `Close` columns.

## Tools

**Python · TensorFlow/Keras · Pandas · NumPy · Scikit-learn · Matplotlib · Seaborn**

## Repository

```text
├── GOOGL.csv
├── INTC.csv
└── Stock_Prediction_LSTM.ipynb
