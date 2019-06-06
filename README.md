# Capstone-2
Second capstone project for the Springboard data science career track.

Project report PDF contains the written report for this project. 

All code for the project is stored in the project code Jupyter notebook.

The objective of this project is to build a LSTM recurrant neural network model to predict Microsoft stock price movement using Keras.

To begin, the data is obtained using custom functions designed to pull the data from the Alphavantage API.

Next, the data is analysed and transformed to a lognormal distribution for use by the model.
After the transformation, the data is split into testing and training sets and reshaped for use in an LSTM model.

Once the data has been prepared, the model is designed and compiled using Keras with TensorFlow backend. 
The model is then trained and optimized on the training set, then tested on the testing dataset. 
Model performance is measured in terms of whether it was able to correctly predict the direction of the stock price movement.
