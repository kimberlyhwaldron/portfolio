## [Project 1](https://kimberlyahealy.github.io/Time_Series_Online_Retail_Data/)

### [Time Series Predictive Modeling <br> Online Retail Data](https://kimberlyahealy.github.io/Time_Series_Online_Retail_Data/)

The data ([OnlineRetail.csv](https://archive.ics.uci.edu/ml/datasets/Online+Retail)) come from all transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based online retail store. The company sells unique gifts and the majority of customers are wholesalers. This report will use techniques to explore the data and use three different time series algorithms to model sales. The conclusion states which model(s) best predict sales and recommendations for further analysis.     
       
The following predictive models are used:        
  - **Model 1: Simple Moving Average**: a weighted average function that identifies the previous pattern in the data and uses that pattern to predict future data points.      
  - **Model 2: Exponential Smoothing**: similar to Simple Moving Average, but contains a smoothing constant which can be tweaked for more responsive or more stable models.      
  - **Model 3: Autoregressive Integrated Moving Average (ARIMA)**: unlilke the previous models, ARIMA considers the correlations among the previous values of the time series to predict future values.    
        
         
The following question is answered:     
  - **Which model best predicts company sales?**
