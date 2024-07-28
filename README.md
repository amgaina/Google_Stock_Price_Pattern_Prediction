# Google Stock Price Pattern Prediction

This repository contains the implementation of a Long Short-Term Memory (LSTM) and Recurrent Neural Network (RNN) model to predict Google stock prices. The model achieves an accuracy of approximately 90% accuracy.

## Introduction
Stock price prediction is a crucial area in financial markets. This project focuses on predicting Google stock prices using an LSTM and RNN model. The model leverages historical stock price data to forecast future prices.

## Dataset
The dataset used in this project includes historical stock prices of Google. The data consists of columns such as Date, Open, High, Low, Close, and Volume. The dataset is preprocessed to make it suitable for training the LSTM model.

## Model Architecture
The model is built using LSTM layers followed by dense layers. LSTM networks are well-suited for time series forecasting due to their ability to capture long-term dependencies. Key components of the model:
- LSTM layers
- Dense layers

## Training
The model is trained on historical stock price data with the following steps:
1. Data Preprocessing: Normalizing the data and creating time series sequences.
2. Model Compilation: Using loss functions and optimizers.
3. Model Training: Training the model on the prepared dataset.

## Evaluation
The model is evaluated using Mean Squared Error (MSE) and achieves an accuracy of approximately 90%. The evaluation is performed on a separate test dataset that was not seen during training.

## Conclusion
The LSTM and RNN model demonstrates strong performance in predicting Google stock price pattern prediction, achieving around 90% accuracy. This model can be further improved and adapted for other stock price pattern predictions.

