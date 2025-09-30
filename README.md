# Time-Series-Analytics-and-Forecasting-of-U.S.-Monthly-Electricity-Prices

Developed and benchmarked multiple time-series forecasting models to predict U.S. monthly electricity prices, incorporating macroeconomic drivers (CPI, natural gas imports) and seasonal factors. Compared deterministic, exponential smoothing, regression, and ARIMA-based approaches, achieving robust forecasts with ~2% error on hold-out data. Delivered insights into long-term pricing trends, cyclical behavior, and inflationary impacts, supporting data-driven decision-making in the energy sector.

**Key Features**:
1. Data Preprocessing: Cleaned and structured 27 years of monthly electricity data; engineered lagged variables, seasonal indicators, and polynomial trends.
2. Exploratory Analysis: Performed decomposition, autocorrelation, and periodogram analysis to detect trends, cycles, and seasonality.
3. Model Development: Built and compared deterministic (piecewise trend + seasonality), exponential smoothing, regression with external regressors (CPI, NGAS), and ARIMA/ARIMAX models.
4. Residual Diagnostics: Conducted ACF/PACF analysis on residuals, applied ARIMA corrections, and validated model assumptions.
5. Performance Evaluation: Benchmarked models using MAPE, RMSE, and MAE; best model achieved ~2% forecast error on hold-out data.
Developed and benchmarked multiple time-series forecasting models to predict U.S. monthly electricity prices, incorporating macroeconomic drivers (CPI, natural gas imports) and seasonal factors. Compared deterministic, exponential smoothing, regression, and ARIMA-based approaches, achieving robust forecasts with ~2% error on hold-out data. Delivered insights into long-term pricing trends, cyclical behavior, and inflationary impacts, supporting data-driven decision-making in the energy sector. 


**Usage**

1. Clone this repo  
2. Open the Jupyter notebook `Timeseries_project.ipynb`  
3. Run cells in sequence:  
   - Data loading & cleaning  
   - EDA & decomposition  
   - Model training & evaluation  
   - Forecasting  
4. Inspect resulting charts, error metrics, and forecasts  

**Tools & Libraries**

1. Python (pandas, numpy, statsmodels, Prophet, matplotlib/plotly)
2. Jupyter Notebook  
3. GitHub for version control  

**Insights & Outcomes**

- Strong seasonal patterns in electricity prices  
- Forecast accuracy evaluated via RMSE / MAPE  
- Forecasts suggest expected trends in future months  

**Version History**

See [`version_log.md`](./docs/version_log.md) for a detailed changelog.

