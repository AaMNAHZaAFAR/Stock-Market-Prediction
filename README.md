# Stock Market Prediction Using RNN, LSTM, and GRU
# Overview
This repository contains the code and resources for predicting stock market prices using Recurrent Neural Networks (RNN), Long Short-Term Memory (LSTM) networks, and Gated Recurrent Units (GRU). The aim of this project is to predict stock prices using advanced machine learning techniques and perform a comparative analysis of their performance.

**Prerequisites**
Install correct versions of libraries:.<br/>
Python: 3.5.x<br/>
TensorFlow: 1.10.0<br/>
Numpy: 1.15.0<br/>
Keras: 2.2.2<br/>
Matplotlib: 2.2.2<br/>
Pandas: 0.23.4<br/>
Seaborn: 0.9.0<br/>
Scikit-learn: 0.19.2<br/>
Statsmodels: 0.9.0<br/>
Dash: 0.21.0<br/>
Plotly: 2.4.1<br/>
Pickle: Python standard library (no specific version)

## Project Structure
### stockprediction.ipynb
This notebook contains the full workflow for predicting stock prices.
Due to the large file size, it has been divided into three files as given below: 

### 1. Stock Exchange Analysis
**File:** `Top_10_countries_Stock_Exchange.ipynb`  
**Description:**  
This notebook focuses on analyzing stock exchanges from 10 different countries. 

### 2. Stock Prediction with Exploratory Data Analysis (EDA)
**File:** `stockprediction_with_EDA.ipynb`  
**Description:**  
This notebook combines both Exploratory Data Analysis (EDA) which provides an in-depth analysis of the dataset.

### 3. Stock Prediction without EDA
**File:** `stockprediction_without_EDA_.ipynb`  
**Description:**  
This notebook focuses solely on the modeling part of stock price prediction. It assumes that the data has already been pre-processed and features have been engineered. This is ideal for users who are only interested in experimenting with different machine learning models.


# Dataset
**Input Format**<br/>
Stock Market Data: I will be utilizing Kaggle's platform, which offers public license to datasets. The dataset is available at the following link: NYSE Dataset on Kaggle. The dataset is in CSV format with four files but i am going to use one of them i.e. prices-split-adjusted.csv.<br/>
**Output Format**<br/>
Predicted Stock Prices: The output will be presented graphically thorough plots containing the actual and predicted closing prices.<br/>
