# Time Series Analysis and Forecasting of Tool Manufacturing in France

This repository contains a comprehensive study of time series analysis and forecasting, specifically focusing on the manufacturing of tools in France over a period exceeding 10 years. The project is divided into three main phases: data analysis and transformation, model fitting, and prediction.

## Project Structure

### 1. Data Analysis and Transformation
In the first phase, we perform a detailed analysis of the time series data. The goal is to transform the data to achieve stationarity—a key requirement for many time series models. Stationarity implies that the statistical properties of the series, such as mean and variance, are constant over time. This step may involve techniques such as differencing, detrending, or seasonal adjustment.

### 2. Model Fitting
Once the data is stationary, we fit various time series models to the data. Specifically, we focus on:
- **ARMA (AutoRegressive Moving Average) Models**: These models are suitable for stationary time series data and combine autoregressive and moving average components.
- **ARIMA (AutoRegressive Integrated Moving Average) Models**: These models extend ARMA by incorporating differencing to handle non-stationary data.

### 3. Prediction and Validation
The final phase involves using the fitted models to forecast future values based on historical data. To ensure the accuracy and reliability of our predictions, we validate our models using several statistical tests:
- **ADF (Augmented Dickey-Fuller) Test**: To check for stationarity.
- **KPSS (Kwiatkowski-Phillips-Schmidt-Shin) Test**: A complementary test to confirm the stationarity of the series.
- **Autocorrelation of Residuals**: To verify that the residuals (errors) of our model are not autocorrelated, indicating a good fit.

## Getting Started

To run the analysis, follow these steps:
