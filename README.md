# Stock Prices Prediction using Machine Learning

This program uses an artificial recurrent neural network called Long Short Term Memory(LSTM) to predict the stock price using past 60 day data.

## Data Source: Yahoo Finacne
Used `pandas_datareader` to read data from Yahoo Finance. This is a great alternative to reading data from APIs. Yahoo Finance is one of the many data sources currently being supported for this library.

Used dynamic dates for end date to GET data up until 'today' everytime the program is ran. 

![](Images/get_stock_quote.PNG)

## Technologies used: Python, Machine Learning, Jupyter Notebook

Currently getting an error rate of ~2%



![](Images/prediction.png)


## Steps:

#### 1. df.shape to get the number of rows and columns in the date  
![](Images/df_shape.PNG)

#### 2. Visualize Historical Data  
![](Images/plot_historical_data.PNG)

#### 3. Filter columns, convert the data into numpy array and get # of rows to train the data on  
![](Images/filter_convert.PNG)

#### 4. Scale the data  
![](Images/scale_data.PNG)

#### 5. Create training dataset
![](Images/training_dataset.PNG)

#### 6. Convert the training data to numpy array and reshape into 3 dimensional
![](Images/convert_reshape_train.PNG)

#### 7. Build and compile the model:
![](Images/build_compile_model.PNG)

#### 8. Train the model
![](Images/train_model.PNG)

#### 9. Create Test Data
![](Images/test_data.PNG)

#### 10. Predict the model, get Root Mean Squared Error(RMSE) and visualize
![](Images/prediction.png)

#### 11. See value vs predicted price in df for comparison
![](Images/prediction_df.PNG)

#### 12. Use the model to predict the price based on last 60 days data
![](Images/predict_price.PNG)