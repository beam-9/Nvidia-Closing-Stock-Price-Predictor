Through the usage of Long Short Term Memory (LSTM) and python, I created a tool which helps predict the future closing stock price of the corporation Nvidia, using the past 120 closing stock price data to train artificial neural network.
To ensure the training data sets could be taken in as an input for the LSTM model, the data set was converted to numpy and reshaped to fit the three dimensional criteria for the LSTM model: number of samples, number of timesteps, and number of features.
To get the model's predicted values, the values were unscaled.
Furthermore, the predicted prices and real prices underwent statistical analysis, the root mean squared value (RMSE) to evaluate the predictor's accuracy and validity.
The data found was then plotted on a line graph for better visualisation.

