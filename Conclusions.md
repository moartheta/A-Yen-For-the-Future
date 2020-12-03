# Conclusions

### Time-Series Forecasting Results

1. Based on your time series analysis, would you buy the yen now?

    *Both models predicted positive returns over the next 5 day period so I would buy the yen now.*

2. Is the risk of the yen expected to increase or decrease?

    *The risk of the yen is expected to increase over the next 5 days.  Unlike the ARMA and ARIMA models, the p-values of the GARCH model would indicate that this model is a good fit.*

3. Based on the model evaluation, would you feel confident in using these models for trading?

    *I wouldn't feel confident in using the ARMA AND ARIMA models at all as the p-values are way too high which indicates a poor fit.  However, the GARCH model seems to be a good fit with p-values under .05*
    
### Linear Regression Forecasting Results

1. Does this model perform better or worse on out-of-sample data compared to in-sample data?

    *The model performs better on out-of-sample data (.415 MSE) than it does with in-sample data (.596 MSE)