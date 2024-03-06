# Mastercard-Stock-price-prediction

Step1: Import necessary libraries.

Step2: Explore the Dataset
       - checked for basic statistics
       - checked for object type 
       - found no null values
       - analysed the correlation matrix
       
Step3: Data Visualisation
       - line graph
       - scatter plot
         Scatter plot between prices and lagged prices, The graph below shows that there is a positive correlation between the original prices 
         and the lagged prices which means higher the lagged price, higher the current price. 
         Hence this piece of info can be used to predict future prices more accurately, trading strategies, etc.
       - Pair plot for key-metrics
       
Step4: Time series analysis
       - Finding moving average and moving std. dev
       
Step5: Split the data into train and test

Step6: Scale the data
       - MinMaxScaler
       
Step7: Used LSTM model

Step8: Plot for Mean Absolute Error

Step: Plot the actual and predicted values


Dataset Link: https://github.com/kalilurrahman/MasterCardStockData/blob/main/Mastercard_stock_history.csv

Dataset Info: https://github.com/kalilurrahman/MasterCardStockData/blob/main/Mastercard_stock_info.csv


Kaggle dataset with columns:-

Date |	Open |	High |	Low |	Close |	Volume |	Dividends |	Stock Split .



 
