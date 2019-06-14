# Capstone-2
Second capstone project for the Springboard data science career track.

Project report PDF contains the written report for this project. 

The project code is broken up into 3 notebooks: Data Wrangling (pulling data from Alphavantage), Exploratory Data Analysis, and Model. 

The objective of this project is to build a LSTM recurrant neural network model to predict Microsoft stock price movement using Keras, then compare the results with the Facebook Prophet model.

To begin, the data is obtained using the Alphavantage API.

Next, the data is analysed and transformed to a lognormal distribution.
After the transformation, the data is split into testing and training sets and reshaped for use in an LSTM model.

Once the data has been prepared, the model is designed and compiled using Keras with TensorFlow backend. 
The model is then trained and optimized on the training set, and tested on the testing dataset. 
Model performance is measured in terms of whether it was able to correctly predict the direction of the stock price movement.

For the Prophet model, the raw data is loaded into a Pandas dataframe with the necessary specifications for use by Prophet. 

Once the dataframe is prepared, the Model is fit with 1 year of training data and makes a prediction for the following year. This process is repeated 9 times for each year after the first.