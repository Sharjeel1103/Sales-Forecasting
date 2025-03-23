# Sales-Forecasting
Project Overview

This project is focused on forecasting retail sales using machine learning models. The dataset includes historical sales data, store information, oil prices, and holiday events. Various models such as Random Forest, XGBoost, ARIMA, LSTM, and Prophet are used to predict future sales.

Prerequisites

Ensure you have the following libraries installed:

pip install pandas numpy matplotlib seaborn scikit-learn xgboost statsmodels tensorflow fbprophet

How to Run the Script

Clone the Repository or Download Files:

git clone <repository_url>
cd sales_forecasting

Prepare the Data:

Ensure the following CSV files are in the working directory:

train.csv

test.csv

stores.csv

oil.csv

holidays_events.csv

Run the Python Script:

python sales_forecasting.py

The script loads and preprocesses the data.

It encodes categorical variables.

Trains and evaluates models.

Compares model performances using error metrics (MSE, RMSE, MAE, R² Score).

Interpret Results:

The script prints performance metrics for each model.

Generates visualizations for trends and correlations.

Model Performance Comparison

The script evaluates different models and selects the best-performing one based on error metrics.

Troubleshooting

If you encounter missing module errors, run:

pip install -r requirements.txt

Ensure all dataset files are present and correctly formatted.

