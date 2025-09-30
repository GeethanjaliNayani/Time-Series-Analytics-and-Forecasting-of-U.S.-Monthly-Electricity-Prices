# Data Dictionary – U.S. Monthly Electricity Prices

- **Date** → Month and year for price observation (format: YYYY-MM or date).  
- **Price** → Electricity price value for that month (unit: e.g. USD per MWh or as per dataset).

1. **Year** → Extracted year from Date.
2. **Month** → Extracted month (numeric or name).
3. **Trend** → Component from time series decomposition.
4. **Seasonal** → Seasonal effect component.
5. **Residual** → Remainder after removing trend + seasonality.
6. **Forecast** → Predicted price values for future dates.
7. **Error Metrics** → Columns like RMSE, MAPE, etc. computed during evaluation.  
