# Bitcoin-Price-Prediction-in-R

Following mentioned are some of the key points related to the project which one should know before working on project:
       
        -The code is done in 'R' Language.
        -The Dataset you need to download as currently i dont have the dataset as because i lost my backup.
         (download any dateset related to this project you can get easily)
        -Enter the path of your dataset before executing the file.
        -Execute each and every line step by step.
         (there is no need to change any line its completely working)
         
         

Objective Behind Developing this project:

        -To implement different functions of R for time series forecasting.
        -To identify correct model for time series forecasting and predictions.
        -To plot graphical representation of bit coin prediction using ggplot2 and different ARIMA model function.
        
Methodology Used for Analysis and Prediction:

        -Forecasting
        -Bayesian linear regression
        -Time series Analysis

        1.Forecasting:
        Forecasting is the process of making predictions of the future, based on past and present data and most commonly by analysis of trends. 
        A common place example might be estimation of some variable of interest at some specified future date.

        2.Bayesian linear regression:
        Bayseian Linear Regression is a very simple machine learning method in which each datapoints is a pair of vectors: the input vector and the output vector.
        Bayesian linear regression allows a fairly natural mechanism to survive insufficient data, or poor distributed data.
        It allows you to put a prior on the coefficients and on the noise so that in the absence of data, the priors can take over.

        3.Time series Analysis:
        Time series analysis comprises methods for analyzing time series data in order to extract meaningful statistics and other characteristics of the data.
        Time series forecasting is the use of a model to predict future values based on previously observed values.  
        
ARIMA MODEL:

        ▪ A popular and widely used statistical method for time series forecasting is the ARIMA model.
        ▪ ARIMA is an acronym that stands for AutoRegressive Integrated Moving Average. 
        ▪ ARIMA model is basically divide into 3 blocks as follows:
                AR- Auto Regressive
                I - Integrated
                MA- Moving Average
        ▪ It is a class of model that captures a suite of different standard temporal structures in time series data.



ACF AND PACF PLOTS :
        
        ▪ ACF and PACF plots: After a time series has been stationeries by differencing, the next step in fitting an ARIMA model is to determine whether AR or MA terms are needed to correct any autocorrelation that remains in the differenced series.
        ▪ By looking at the autocorrelation function (ACF) and partial autocorrelation (PACF) plots of the differenced series, you can tentatively identify the numbers of AR and/or MA terms that are needed.

STEPS IN ARIMA MODEL:

        i. Examine your data:
                Tsclean()
        ii. Decompose Your data:
                Decompose()
        iii. Stationary(Test if the series is stationary):
                Adf.test()
        iv. Autocorrelations and choosing model order.
        v. Choose order of ARIMA by examining ACF and PACF plots.
        vi. Fit an ARIMA model.
        vii. Evaluate and iterate.
        
        
