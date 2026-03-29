# 📉 Customer Churn Prediction using Time Series Forecasting

## 🎯 Overview
This project leverages advanced time-series analysis to predict future customer churn. By analyzing historical customer activity data, the project implements an end-to-end SARIMA (Seasonal Autoregressive Integrated Moving Average) forecasting model to identify temporal patterns and predict potential drop-offs, enabling proactive retention strategies.

## ⚙️ Tech Stack
* **Language:** Python
* **Time Series Modeling:** Statsmodels (SARIMA)
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib

## 🚀 Key Features
* **Rigorous Data Preprocessing:** Includes stationarity checks, differencing, and seasonal decomposition to properly format historical data for time-series modeling.
* **SARIMA Implementation:** Utilizes the Statsmodels library to build and train a forecasting model that accounts for both trend and seasonality in customer behavior.
* **Performance Evaluation:** Validates the model's accuracy through comprehensive residual analysis and visualizes the forecasted churn trends.

## 📁 Repository Structure
* `ARIMA_churn_pred.ipynb`: The primary Google Colab Jupyter Notebook containing the complete end-to-end workflow, including exploratory data analysis, stationarity tests, model training, and visual outputs.
* `arima_churn_pred.py`: The exported Python script version of the notebook for clean code review.

## 📂 Dataset
> **Note:** The historical customer activity dataset used to train this model has been excluded from this repository to adhere to version control best practices regarding file size.
* The raw dataset can be accessed here: [Insert link to dataset, e.g., Kaggle link]

## 🛠️ How to View
Since this project was developed in Google Colab, the easiest way to view the analysis and visual outputs is to open `ARIMA_churn_pred.ipynb` directly here on GitHub.
