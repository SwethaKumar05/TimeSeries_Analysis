# TimeSeries_Analysis

In my time series analysis project, I aimed to predict future sales by examining historical data. The analysis began with decomposing the time series using seasonal decomposition to identify underlying patterns such as trend, seasonality, and residuals. This step helped in isolating the seasonal component of the data, allowing for a clearer understanding of periodic fluctuations.

Next, I applied the Augmented Dickey-Fuller test to check for stationarity, which is crucial for making reliable time series predictions. Ensuring the data was stationary enabled more accurate model predictions. I also used autocorrelation plots to explore the relationships within the data points over time, helping identify lag periods where past values significantly correlated with future values.

To smooth the data and reduce noise, I implemented exponential smoothing, which assigns exponentially decreasing weights to past observations. This approach allowed me to produce a smoothed version of the time series, making it easier to model.

Finally, I used the SARIMAX (Seasonal AutoRegressive Integrated Moving Average with eXogenous factors) model to make predictions. This model was chosen for its ability to handle complex seasonal patterns and external factors, providing robust and accurate forecasts. The project's overall goal was to effectively capture and model the intricate patterns within the time series data to predict future sales accurately.
