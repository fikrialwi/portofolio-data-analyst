# 📈 Microsoft (MSFT) Stock Price Analysis and Forecasting (2015–2021)

This project conducts a comprehensive analysis of Microsoft's (MSFT) stock price movements from 2015 to 2021. It focuses on identifying underlying trends, evaluating the stationarity of the time series, and building an ARIMA model for future price forecasting.

## 📊 1. Stock Price Trends & Volatility

* **Strong Upward Trend:** MSFT's stock price exhibited a robust and consistent upward trend throughout 2015-2021, with significant acceleration from late 2019.
* **Market Sensitivity:** Price movements, particularly declines in late 2018 and early 2020, highlight the market's sensitivity to external events (e.g., macroeconomic shifts, COVID-19 pandemic).
* **Volume Activity:** Significant spikes in trading volume often coincided with periods of substantial price movement, especially during market turmoils, indicating high investor participation.

## 📉 2. Time Series Decomposition

* **Dominant Trend Component:** Time series decomposition clearly shows that the **trend component is the primary driver** of MSFT's stock price movement, exhibiting clear exponential growth.
* **Insignificant Seasonality:** Analysis revealed **no significant seasonal patterns** influencing MSFT's stock price. Price movements are primarily driven by fundamental factors and random fluctuations rather than recurring time-based patterns.
* **Residuals Reflect Volatility:** The residual component, while appearing random, displayed periods of varying volatility (e.g., surges in early 2020), reflecting the market's response to unforeseen events.

## ⏱️ 3. Stationarity Analysis

* **Non-Stationary Original Series:** The Augmented Dickey-Fuller (ADF) test (p-value: 0.9982) and the ACF plot confirmed that the original MSFT closing price series was **non-stationary** due to its strong upward trend.
* **Stationarity Achieved with Differencing:** Applying first-order differencing (`d=1`) successfully made the time series stationary (ADF test p-value: 0.0000). This is a crucial prerequisite for ARIMA modeling.
* **Autocorrelation Removed:** ACF and PACF plots of the differenced series demonstrated the effective removal of significant autocorrelation, indicating that the series was ready for modeling.

## 🔮 4. ARIMA Modeling & Evaluation

* **Model Selection:** An ARIMA model was built using optimal parameters identified by `auto_arima` (with `d=1` based on stationarity analysis).
* **Performance Comparison:**
    * **ARIMA Model:** RMSE: 4.5418, MAE: 3.3377
    * **Baseline Model (Predicting Yesterday’s Price):** RMSE: 4.6514, MAE: 3.3771
* **Modest Improvement:** The ARIMA model showed **slightly better predictive performance** than the simple 'previous day' baseline, indicating it captured some predictable structure beyond a pure random walk.
* **Residual Diagnostics:** Residual analysis confirmed the model's adequacy. Residuals fluctuated randomly around zero, and the Ljung-Box test (p-value: 0.7235 > 0.05) indicated no significant remaining autocorrelation, resembling white noise. However, the Q-Q plot suggested 'fat tails' in the residual distribution, typical for financial data.

## 💡 5. Key Takeaway

> Forecasting stock prices using only historical price data is challenging due to efficient market dynamics and external factors. While ARIMA offers marginal improvements over a random walk, incorporating advanced techniques and exogenous variables is crucial for better predictive power.

## 🛠️ 6. Tools Used

* Python (Pandas, Plotly, Matplotlib, NumPy)
* Time Series Libraries (pmdarima, statsmodels)
* Statistical Testing (Augmented Dickey-Fuller, Ljung-Box)
* Time Series Decomposition & Visualization
* Error Metrics (RMSE, MAE)

---

Author: Dzulfikri Alwi Muhammad (📧 dzulfikrialwim@gmail.com)

Dataset Source: MSFT Historical Stock Prices ([Kaggle](https://www.kaggle.com/datasets/vijayvvenkitesh/microsoft-stock-time-series-analysis))

Period Covered: 2015–2021
