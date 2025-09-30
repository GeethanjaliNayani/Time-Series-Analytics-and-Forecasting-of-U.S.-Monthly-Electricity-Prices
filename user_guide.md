# User Guide – Electricity Price Forecast Dashboard / Notebook

This notebook and related visualizations let you explore and forecast U.S. electricity prices time series.

## Sections

1. **Data Loading & Cleaning**  
   Load the CSV, parse dates, handle missing values.

2. **Exploratory Data Analysis (EDA)**  
   - Time series plot of prices  
   - Seasonality and trend observations  
   - Autocorrelation / PACF  

3. **Time Series Decomposition**  
   Decompose into trend, seasonal, residual components.

4. **Model Training & Validation**  
   Train forecasting models (ARIMA, SARIMA, etc.), split data into train/test, evaluate using RMSE / MAPE.

5. **Forecasting**  
   Generate forecasts for future months, plot predicted vs actual.

6. **Visualization & Interpretation**  
   Use line plots, error summary tables, forecast intervals.

## How to interpret outputs

1. **Trend component** shows long-term upward/downward movement.
2. **Seasonal component** reveals repeating patterns each year.
3. **Residual** should ideally resemble white noise (no pattern).
4. **Forecast vs Actual plots** show how well model predicts.
5. **Error metrics** (RMSE, MAPE) help compare model performance.
6. Use sliding windows or rolling forecasts for robust validation
7. Check residuals for autocorrelation to validate model assumptions
8. Compare multiple models and choose based on lowest error metrics  
