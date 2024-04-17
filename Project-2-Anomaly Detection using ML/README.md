# Project-2- Anomaly Detection WTI Oil Prices using LTSM Autoencoders

The ability to detect anomalies in crude oil prices has practical application in the financial and energy sectors. Detecting abnormal price movements early can help to make informed decisions and mitigate potential risks. The main goal of this project is to build an Anomaly Detection model based on LTSM Autoencoders for the time series of the WTI Oil Prices. 

Stock prices over days/months/years are a clear example of time series. The time series data has a unique aspect, past values can be used to predict future values. However, sometimes unpredictable anomalies can occur. Nowadays, the Artificial Intelligence algorithms are a powerfull tool to address this challenging problem. In specific, this project illustrate the performance of LTSM autoencoder.


LSTM stands for Long Short-Term Memory. LSTMs are a type of Recurrent Neural Network (RNN) designed to model temporal sequences and long-range dependencies more accurately than regular Recurrent Neural Networks.


An autoencoder is a type of neural network designed to copy its input to its output. Internally, it has a hidden layer that encodes the input into a representation. By training the network to minimize the difference between the input and output, it learns efficient data encodings in the hidden layer.


An LSTM autoencoder combines both of these concepts. It uses LSTM layers to learn representations of temporal input sequences. The training process creates two LSTM models — an encoder to reduce sequences into vector representations and a decoder that tries to replicate vectors back to original sequences.


![Figure](https://github.com/DrAdrianDC/Portfolio-for-Data-Science/assets/157868503/59dc7998-171f-44e3-985b-f29f3db0103b)









# Requirements

* Python 3.8.3
* TensorFlow 2.10.0
* Pandas 1.0.5
* Numpy 1.23.4
* Scikit-learn 1.3.2
* Keras 2.10.0


# Dataset

In this project I am using the open source yfinance library to get financial data from Yahoo Finance.
