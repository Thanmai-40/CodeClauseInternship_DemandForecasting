# Retail Sales Demand Forecasting

## Project Overview
This project involves analyzing historical sales data to forecast future demand for retail store products. The goal is to identify trends, seasonality, and patterns to support inventory management and business planning. The project uses various time series analysis techniques and models to ensure accurate predictions.

## Dataset
The dataset used in this project contains sales records for multiple items across various stores. Key columns include:
- `store`: The store identifier
- `item`: The item identifier
- `sales`: The number of units sold
- `date`: The date of the sales transaction

## Tools and Libraries
- Python
- Pandas
- Matplotlib
- sklearn
- Statsmodels

## Steps Involved
1. **Data Preprocessing**
   - Loaded and explored the dataset.
   - Aggregated sales data to monthly frequency for better trend analysis.

2. **Exploratory Data Analysis (EDA)**
   - Visualized sales trends over time.
   - Conducted autocorrelation and partial autocorrelation analysis to understand seasonality and lags.

3. **Modeling**
   - Applied SARIMA (Seasonal ARIMA) model for time series forecasting.
   - Evaluated model performance using confidence intervals and visual inspection of the forecast.
   - Also included hot winters forecast.

4. **Forecasting**
   - Generated monthly and yearly sales forecasts with confidence intervals.

## Key Findings
- Seasonal patterns were observed in sales, indicating fluctuations at regular intervals.
- The SARIMA model captured both trend and seasonality effectively, providing reliable forecasts.
- Take a look at the jupyter notebook for detailed explanation.
