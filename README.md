Stock Price Prediction using LSTM (Toyota & BMW)

This repository contains two deep learning projects that use LSTM (Long Short-Term Memory) networks to predict stock prices.
The models are trained on historical stock data of: BMW and Toyota

1. Project Overview

 Stock prices are time-series data, and traditional models struggle to capture long-term dependencies.
 This project uses LSTM neural networks, which are well-suited for sequence prediction tasks.
Each notebook includes:
* Data preprocessing
* Feature scaling
* Time-step sequence creation
* LSTM model building
* Training and prediction
* Visualization of results

2. Files in this Repository

* Toyota Stock Prediction.ipynb → Predicts Toyota stock closing prices
* BMW Stock Prediction.ipynb → Predicts BMW stock closing prices

3. Technologies Used:
* Python 
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* TensorFlow / Keras

4. How It Works

 - Load stock dataset
 - Select `Close` price
 - Normalize data using MinMaxScaler
 - Create sequences (time steps = 60)
 - Train LSTM model
 - Predict future prices
 - Compare predicted vs actual values

5. Model Highlights

* Uses 60-day time window for prediction
* Applies MinMax Scaling
* Captures trends using LSTM layers
* Visual comparison of predictions vs real data

6. Future Improvements

* Add more stocks
* Use GRU / Transformer models
* Hyperparameter tuning
* Deploy as a web app
