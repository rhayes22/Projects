This is a series of independent projects that I have completed in Python.  As of now, I have (1) project in the repository, which is a Stock Predictor.

Stock Predictor:

Description: Uses data from the previous 60 days to predict the stock price at close one day into the future. As of now, the functionality is low and the accuracy is also very low.
Each trial gives a different prediction for the following day, so it may be better to run this prediction many times to get a more accurate prediction.  

Modules Used:
 - numpy
 - matplotlib.pyplot
 - pandas
 - pandas.datareader
 - datetime
 - sklearn.preprocessing
 - tensorflow.keras.modules
 - tensorflow.keras.layers
 
 Functions:
 - closingpriceprediction(company) - predicts the price of a stock at close the following day
 - openingpriceprediction(company) - predicts the price of a stock at open the following day

Functionality: Gives a graph with two lines, the actual stock price and the previous prediction.  After closing this graph, a prediction is printed in the terminal for the 
following day's closing price.  

How to improve: 
 - Research the different modules used to find out further functionality for each of them.
 - Research a more advanced version of this project, possibly an extension of the previous video that was used.
 - Research more about machine learning in Python
