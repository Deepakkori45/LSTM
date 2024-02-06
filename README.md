# Indian Stock Forecasting using LSTM
# Introduction
This project focuses on predicting stock prices using a Long Short-Term Memory (LSTM) model. We utilize historical data including the closing price of the stock to train the model and make predictions. **We collected historical stock data including the closing prices.**

# Data Preprocessing
Date vs Closing price graph
![image](https://github.com/Deepakkori45/LSTM/assets/111627339/3fca828c-d3ac-4ee5-a647-907e1d05a3f5)

Created a sliding window approach where each row considers the closing prices of the last 3 days and predicts the 4th day's price.


# LSTM Model
Input Layer: (3,1) - representing a sequence length of 3 days and 1 feature (closing price).
Activation Function: ReLU.
Optimizer: Adam

# Visualization
Plotted graphs for the training, validation, and test sets to visualize the model's performance.
![image](https://github.com/Deepakkori45/LSTM/assets/111627339/ed7a1d3c-32a8-42ff-bd35-4f01c998ab61)


# Future Predictions
Trained the model on the entire dataset.
Made predictions for the next three days' stock prices.
![image](https://github.com/Deepakkori45/LSTM/assets/111627339/091ac178-718c-42bc-816f-dc883834a715)

# Conclusion
This project demonstrates the application of LSTM models for stock price prediction. Further optimization and can be explored to improve the model's accuracy.

