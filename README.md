# Stock Price Prediction

The notebook contains various methods of predicting the stock price of Nifty50 (^NSEI).
Following Techniques are used:
- ARIMA
- SARIMA
- Prophet
- Long Short Term Memory (LSTM) Model


# Project Structure

1. **Data Collection:**
   - Utilize the Yahoo Finance API to fetch historical stock data for the selected companies.

2. **Data Preprocessing and EDA:**
   - Checked for stationarity of data.
   - Plotted ACF and PACF plots
   - Decomposed and plotted the Trend, Seasonality and Residual

3. **Applying Statistical Model:**
   - Used the following statistical models for price prediction and plotted the graphs:
     * Auto-Regressive Integrated Moving Average (ARIMA)
     * Seasonal Auto-Regressive Integrated Moving Average (SARIMA)
     * Prophet

4. **Integrating Features for LSTM Model:**
   - Integrated Indicators as features to the dataset for the LSTM model:
   - Following indicators were added:
     * RSI Indicator
     * EMA - 12 and 26 period
     * ATR Indicator

5. **Applying the LSTM Model:**
   - The LSTM Model with a Linear Regressor layer at the end was used to predict the prices of the stock.
   - Mean Squared Error (MSE) Loss was used as metrics.
   - Visualisation plots were created for actual prices and predicted prices in the training and testing sets.
  
