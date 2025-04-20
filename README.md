# Financial-Time-Series-Anomaly-Detection

This project detects anomalies in stock price trends using both statistical indicators and machine learning techniques. It helps identify unusual patterns and potential market manipulations in financial data.

---

## Objective

To build a tool that:
- Downloads historical stock price data
- Computes financial indicators (SMA, EMA, RSI, Bollinger Bands)
- Detects anomalies using unsupervised learning (Isolation Forest, DBSCAN)
- Forecasts trends using LSTM/Prophet
- Visualizes anomalies on time-series charts

---

## Dataset

- **Source:** Yahoo Finance
- **Dataset Used:** Stock data for selected companies (e.g., AAPL, TSLA, AMZN)
- **Duration:** Last 5 years (Daily granularity)
- **Format:** Open, High, Low, Close, Volume

---

##  Techniques & Tools

### Indicators Calculated:
- Simple Moving Average (SMA)
- Exponential Moving Average (EMA)
- Relative Strength Index (RSI)
- Bollinger Bands

### Models Applied:
- **Unsupervised Anomaly Detection:**
  - Isolation Forest
  - DBSCAN
- **Time-Series Forecasting:**
  - LSTM (Keras)
  - Prophet (Facebook’s library)

### Libraries Used:
- `yfinance`, `pandas`, `numpy`
- `matplotlib`, `seaborn`, `plotly`
- `sklearn`, `statsmodels`, `fbprophet`
- `tensorflow` (for LSTM)
