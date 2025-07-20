# Machine Learning for FX Currency Rate Prediction

### [View the Full Dissertation PDF](./Vashisht_Neel_FX_Prediction_Dissertation_2024.pdf)

---

## Project Overview

This repository contains the code, analysis, and final report for my BSc Computer Science dissertation at the University of Manchester. The project is an end-to-end investigation into the application of various machine learning and statistical models for predicting USD/JPY foreign exchange rate trends.

The core of the project involved developing a data pipeline to ingest and process over 10 years of historical financial data, followed by the implementation, training, and rigorous evaluation of three distinct forecasting models. The full methodology, theoretical background, and critical analysis of the results are detailed in the accompanying dissertation PDF.

## Key Features

*   **Comprehensive Data Preprocessing:** Includes techniques for handling time-series data, such as Winsorization for outlier management, stationarity testing (ADF tests), and differencing.
*   **Multiple Model Implementation:**
    *   **ARIMA:** Explores both offline and online (rolling window) implementations of the classical statistical forecasting model.
    *   **LSTM:** A deep learning (Recurrent Neural Network) approach to capture long-term dependencies in the time-series data.
    *   **XGBoost:** Implements both regression (predicting the rate) and classification (predicting the direction of change) models using the powerful gradient boosting framework.
*   **Feature Engineering:** Demonstrates the impact of incorporating external market data (S&P 500 and Nikkei 225 stock indices) to improve model performance.
*   **Rigorous Evaluation:** Utilises a full suite of statistical metrics (RMSE, MSE, R², etc.) and data visualisations to compare the performance of each model.

## Technologies & Libraries

*   **Language:** Python
*   **Core Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
*   **Modelling:** Statsmodels, `pmdarima`, Keras (with TensorFlow), XGBoost
*   **Data Source:** `yfinance`

## How to Run

1.  Clone the repository:
    `git clone https://github.com/neelvash/Currency-Exchange-Rate-Prediction.git`
2.  Install the required dependencies:
    `pip install -r requirements.txt`
3.  Open the Jupyter Notebooks (`.ipynb` files) to view the code for each model.

---