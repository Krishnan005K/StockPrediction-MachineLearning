# StockPrediction-MachineLearning
 
# Stock Price Prediction with LSTM

This project aims to predict the stock price of Netflix (NFLX) using a Long Short-Term Memory (LSTM) model. The model is trained on historical stock price data and is capable of predicting future stock prices based on past trends.

# Dataset
The dataset used for this project is the historical stock price data of Netflix (NFLX), which is obtained from the Yahoo Finance API. The dataset includes the opening stock price for each trading day.

# Implementation
The implementation of the project is done in Python using the following libraries:

Pandas for data manipulation

NumPy for numerical operations

Matplotlib for data visualization

Scikit-Learn for feature scaling

TensorFlow and Keras for building and training the LSTM model


# Steps
**Data Preprocessing:** The dataset is loaded and preprocessed to prepare it for training.

**Feature Scaling:** The opening stock prices are scaled using Min-Max scaling.

**Data Sequencing:** The dataset is converted into sequences of data with a specified number of timesteps.

**Model Building:** An LSTM model is built using TensorFlow and Keras.

**Model Training:** The model is trained on the training dataset.

**Prediction:** The model is used to make predictions on the test dataset.

**Results Visualization:** The predicted stock prices are compared with the actual stock prices, and the results are visualized using Matplotlib.


# Result

The LSTM model achieves a certain level of accuracy in predicting the stock prices of Netflix. However, the accuracy may vary depending on the dataset and the model parameters.

