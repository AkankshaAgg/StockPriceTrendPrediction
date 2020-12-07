# StockPriceTrendPrediction

Model is build to predict the upward and downward trend of stock prices of Google. 

Training dataset include stock price of Google between Jan, 2011 to April, 2020 i.e. around 2400 days. Testing dataset include stock price of Google in the month of May, 2020. 
* Robust and high dimensional model is build using **Recurrent Neural Networks** with 4 layers of **Long Short-term memory**. 
* Dropout regularisation is used to avoid overfitting.
* Timesteps considered are 60 days i.e. 3 months.

Following is the trend obtained for predicted stock price of May, 2020:

![](https://github.com/AkankshaAgg/StockPriceTrendPrediction/blob/master/output.PNG)
