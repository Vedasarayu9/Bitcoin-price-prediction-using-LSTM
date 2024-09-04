# Bitcoin-price-prediction-using-LSTM

# Introduction
This repository contains Python code for predicting Bitcoin prices using a Long Short-Term Memory (LSTM) neural network. The LSTM model is trained on historical Bitcoin price data and is used to forecast future prices.

# Requirements
- **Python 3.8 or higher**
- **Required Python libraries**
  - **TensorFlow/PyTorch**
  - **NumPy**
  - **Pandas**
  - **Scikit-learn**
  - **Matplotlib**
  - **Seaborn**

# Install dependencies:
- **pip install pandas**
- **pip install numpy** 
- **pip install matplotlib** 
- **pip install keras** 
- **pip install tensorflow**

BitcoinPricePrediction.ipyb script will load the data, preprocess it, create training and testing sets, build the LSTM model, train the model, make predictions on test data, and visualize the results.

# Model Architecture

The LSTM model used in this project consists of the following layers:
- **Input layer:** Takes the sequence of historical prices as input.
- **LSTM layers:** Process the input sequence and capture long-term dependencies in the data.
- **Dense layer:** Output layer that predicts the future price.

# Evaluation
The model's performance is evaluated using appropriate metrics, such as mean squared error (MSE), root mean squared error (RMSE), and mean absolute error (MAE).

# Customization
You can customize the model architecture, training parameters, and evaluation metrics to suit your specific needs. Experiment with different hyperparameters to optimize the model's performance.

