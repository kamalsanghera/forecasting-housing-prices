# forecasting-housing-prices
Forecasting housing market trends using ARIMA, ETS, and Holt models

This project uses historical real estate sales data (2007–2019) to forecast 3-bedroom house prices using multiple time series models.

## Objective
To evaluate and compare forecasting models that can help investors, developers, and analysts make informed housing market decisions.

## Models Used
- ARIMA
- Holt’s Linear Trend
- Damped Holt
- ETS (Exponential Smoothing)

## Evaluation Metrics
- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- ACF (Autocorrelation of residuals)
- Confidence intervals for forecast accuracy

## Tools Used
- R
- `forecast` and `fpp3` packages
- RStudio

## Outcome
Holt’s model delivered the most accurate forecast for 3-bedroom house prices. The report includes visualizations and residual diagnostics. Forecasts extend through 2024 based on historical pre-COVID data.
