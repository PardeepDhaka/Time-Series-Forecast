# Time-Series-Forecast
Built a time series forecasting model on UTL data to predict future trends. Used historical patterns to forecast key metrics with evaluation via RMSE and MAE.


Time Series Forecasting on UTL Data

This project focuses on forecasting key trends in UTL (Utility) data using time series analysis techniques. By analyzing historical data, the goal is to accurately predict future values and understand underlying seasonal, trend, and cyclical patterns.
Key Features ->

    Time Series Modeling: Implemented forecasting models like ARIMA, Exponential Smoothing, and Prophet.

    Data Preparation: Handled missing values, outliers, and ensured stationarity where required.

    Feature Engineering: Extracted temporal features (e.g., month, lag, rolling averages) to enhance predictive performance.

    Evaluation Metrics: Assessed model accuracy using RMSE (Root Mean Square Error), MAE (Mean Absolute Error), and MAPE.

    Rolling Forecasting: Performed backtesting using rolling forecasts to measure real-world model performance over time.

Technologies Used ->

    Python (Pandas, NumPy, Statsmodels, scikit-learn, Prophet)

    Jupyter Notebook for analysis and model development

    Matplotlib & Seaborn for visualizations

Dataset ->

The dataset consists of timestamped utility usage records with various numerical features. Time-based aggregations and resampling techniques were applied to prepare the data for modeling.
Results->

The best-performing model successfully captured seasonality and produced low forecast error across test periods. The approach is scalable and adaptable for similar forecasting tasks in utility and energy domains.
