# Microsoft_stock-ARIMA

This project focuses on forecasting Microsoft’s stock closing prices using Time Series Analysis with ARIMA models.
The dataset contains historical daily stock prices for Microsoft Corporation, with the primary goal being to predict future closing prices based on historical trends.

Methodology
1. Exploratory Data Analysis (EDA)
Plotted the historical closing price of Microsoft stock.

Visualized Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF) to identify lag dependencies.

2. Stationarity Check
Conducted the Augmented Dickey-Fuller (ADF) test to statistically check for stationarity.

Differenced the time series to achieve stationarity (first-order differencing).

3. ARIMA Modeling
Fitted an ARIMA model to the stationary series.

4. Forecasting
Generated out-of-sample forecasts for future stock closing prices.
