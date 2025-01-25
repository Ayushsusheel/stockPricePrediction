# _Stock Price Prediction_
Hi, This repository consists the project Stock Prediction where I have predicted the closing price of Google Stock. ( Just for educational purpose )

# Steps Included :-

1) **Data Visualization :-**
   • The very 1st step is to import the necessary libraries.
   • Here we have used the matplotlib, seaborn and plotly libraries for data
     visualization.

2) **Data Preprocessing :-**
    • In Data preprocssing various steps are involved which are very important to
      perform because this data is going to be used further in the model                 implementation.
    • These Steps are :-
      ✓ Handle the missing values
      ✓ Data Transformation
      ✓ Data Normalization
      ✓ Outlier Removal
      ✓ Feature Selection

3) **Model Implementation :-**
    • Comparing Moving average for 250 days with Original Stock
      closing price
    • Now comes the train and test split part where we used 70% of data
      for training and 30% of data for testing
    • We used Sequential Model and “LSTM” (Long Short- Term
      Memory) layers in order to find the predicted values.
    • Predicting the Values using predict() method and passing x_test as
      a parameter to it.

4) **Model Evaluation :-**
  Now Calculating the Evaluation Metrics one by one as :-
  • MAE = 2.08
  • MSE = 7.5
  • RMSE = 2.75
  • MAPE = 1.37
  • R2 = 0.97

_**Predicting the next 30 days values + After predicting the value’s we are then plotting a graph to visualize the data more
clearly.**_
