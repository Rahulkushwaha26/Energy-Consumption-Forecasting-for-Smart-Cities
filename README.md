# Intelligent Energy Consumption Forecasting for Smart Cities
An intelligent electricity forecasting system for India using LSTM, ARIMA, SARIMA, and Random Forest on monthly state-wise capacity data (2019–2024). Compares model performance and projects renewable energy growth up to 2030 to support smart city planning.

## Dataset
India Monthly Electricity Consumption (2019–2024) from Kaggle. Covers 37 states and union territories, 15+ fuel types, 72 monthly observations in Megawatts (MW).

## Models
Linear Regression — baseline trend projection
Random Forest — lag-based non-linear forecasting
LSTM — best accuracy, captures seasonal patterns
ARIMA (2,1,2) — statistical trend modeling
SARIMA (1,1,1)(1,1,1,12) — seasonal time-series modeling

## Evaluation Metrics
Mean Absolute Error (MAE), Root Mean Square Error (RMSE), Mean Absolute Percentage Error (MAPE)

## Key Results
India's renewable share grew from 24% (2019) to 30% (2024)
LSTM achieved the lowest MAE and RMSE among all models
Solar is the fastest growing fuel type
Scenario projections show 36–50% renewable share by 2030

## Tech Stack

Python, TensorFlow/Keras, Scikit-learn, Statsmodels, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

## Authors
Rahul Kushwaha
Supervisor: Dr. Kashav Ajmera, Assistant Professor, Dept. of CSE and IT, JIIT Noida
