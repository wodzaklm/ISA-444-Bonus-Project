# ISA-444-Bonus-Project
Duke Energy data forecasting project

## Energy Forecast app
This application contains various time series forecasting models from the following packages:
- StatsForecast
- sklearn
- LightGBM
- MLForecast
- TimeCopilot

## Features
- Upload time series data in CSV format
- Choose from multiple forecasting models:
    - Naive
    - Seasonal Naive
    - AutoETS
    - AutoARIMA
    - Lasso 
    - KNeighbors Regressor
    - Random Forest Regressor
    - LightGBM Regressor
    - TimeCopilot Forecaster
    - Chronos
    - Moirai
    - TimesFM
 
- View performance metrics (ME, MAE, RMSE, MAPE)
- Visualize forecasts

## Using the App
1. Upload a CSV file with time series data that contains:
   - `unique_id` column: Unique identifier for each time series
   - `ds` column: Date/timestamp
   - `y` column: Target values
2. Configure:
   - Frequency (D = daily, H = hourly, M = monthly, etc.)
   - Evaluation strategy and parameters
   - Select models and their parameters
3. Click "Run Forecast" to see results

## Example of Data Format:
unique_id, ds, y
series1, 2025-12-2, 444

series2, 2025-12-3, 414

series3, 2025-12-4, 404


## About StatsForeacst
StatsForecast is a Python library that provides statistical forecasting algorithms for time series data. It is fast and scalable and offers many classical forecasting methods.

For more information, visit Nixtla's StatsForecast repository.

## About Scikit-learn
Scikit-learn is a Python library containing simple and efficient tools for predictive data analysis. It is built to be widely accessible and reusable in various contexts.

For more information, visit https://scikit-learn.org/stable/#

## About LightGBM
LightGBM is a gradient boosting framework that uses tree based learning algorithms. It is designed to be distributed and efficient with the advantages of faster training speed and higher efficiency, lower memory usage, better accuracy, and a capability of handling large-scale data. 

For more information, visit https://lightgbm.readthedocs.io/en/stable/

## About MLForecast
MLForecast is a framework to perform time series forecasting using machine learning models, with the option to scale to massive amounts of data using remote clusters.

For more information, visit https://nixtlaverse.nixtla.io/mlforecast/index.html

## About TimeCopilot
TimeCopilot is an open-source, agentic framework that provides a unified API for the following families of models:
- Time series forecasting
- Integrating foudnation models
- Classical statistical models
- Machine learning
- Neural network

For more information, visit https://timecopilot.dev/model-hub/
