# The Forecast of Stock Price And Its Trend Based on SVM

Introduction:  
1：We crawle 2 million titles of text data in Oriental Wealth website using Python. And an investor sentiment index is constructed based on Baidu Index, Elastic Net and PCA.  
2: Using the 1500 trading days of the ShangZheng Stock Exchange Index from March 24(2011) to May 24(2017), a stock market timing trading model is established based on SVM. After adjusting the parameters using the Sliding Window method, the future trend of the stock market is forecasted to get the operational signal for each future trading day.  
3: The investor sentiment index is taken as a feature of the data into the SVM, to explore whether it can improve the prediction performance of the model.  
4: The visualization of forecasting results.    

Requirements:  
 Python2.7  
 Tushare  
 Scikit_Learn  
 Pandas  
 Numpy
