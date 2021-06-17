# Stock Price Analysis Using ARIMA
Time Series Prediction using **ARIMA** (AutoRegressive Integrated Moving Average) and analysis of the results I obtained using this method when predicting **Tesla** stock prices from 2010 to 2020.

## Inspiration
**"Is there a way to explain the recent surge with technical indicators alone?"**

## Dataset
> **Data from https://finance.yahoo.com/quote/TSLA**

## Project Overview

Investment firms, hedge funds, and even individuals have been utilizing financial models to comprehend market behavior better and make profitable investments and trades. The abundance of "data" accessible and available in the form of chronicled stock prices and company performance insights make it suitable for machine learning algorithms to process and conduct quantitative analysis to build predictive models.

**The new age of algorithms has dawned upon us.**

Hence, this project utilizes the ARIMA model for base predictions and then builds a Deep Learning model to improve it further. Stock prices will be predicted for Tesla.

## Why Tesla?
![](https://www.profitconfidential.com/wp-content/uploads/2020/10/Tsla.png)

Tesla's stock has surged more than 20,000% since it went public in 2010; it has been rocketing recently, with a crazy +100% spike in the last 30 days alone. The stock prices have nearly Quintupled. 2020 was the greatest year for Tesla stock since its inception.
While the company has always been prone to rapid growth spurts, last year’s upward trajectory has been truly remarkable due, not just to its rapid pace, but also to the context: all these gains happened in the midst of the coronavirus pandemic.

Now, the question arises: **Has the stock hit its ceiling, or is there yet room to grow?**

For all the momentum swelling behind TSLA stock in 2020, 2021 may be even better.
> **Analyst Take**
- The future of Tesla stock is uncertain as to whether it can replicate the absurd gains it experienced in 2020.

- But, what is far more certain is that the stars are aligning for a TSLA stock breakout at just the right time.

##  Why ARIMA?
**The acronym of ARIMA stands for:**

- AutoRegressive => The model takes advantage of the connection between a predefined number of lagged observations and the current one.
- Integrated => Differencing between raw observations (eg. subtracting observations at different time steps).
- Moving Average => The model takes advantage of the relationship between the residual error and the observations.

**ARIMA can lead to particularly good results if applied to short time predictions.**

## Steps 

- **Importing Libraries**
- **Data Preprocessing**
- **Tesla Stock Market Analysis from 2010-2020**
- **Tesla ARIMA (AutoRegressive Integrated Moving Average) Time Series Prediction**

## Conclusion

First of all, through the exploratory data analysis performed on this dataset, many intrigiung inferences could be drawn.
It can be concluded that accurate modeling and designing of appropriate variables may lead to models using which stock prices and stock price movement patterns can be very accurately predicted. The results clearly indicate that the ARIMA-based model that uses the ten years data as input for predicting the open value of the time series shows a satisfactory accuracy.

## Bibliography

- [ARIMA for Time Series Forecasting](https://machinelearningmastery.com/arima-for-time-series-forecasting-with-python/)
- [Symmetric mean absolute percentage error](https://en.wikipedia.org/wiki/Symmetric_mean_absolute_percentage_error)
- [More on ARIMA](https://letianzj.github.io/arima-garch-model.html)
- [Stock Price Prediction Using Machine Learning](https://arxiv.org/abs/2009.10819)
- [EDA of stock-market using time series](https://usharbudha-dev09.medium.com/eda-of-stock-market-using-time-series-9662fd18bfc5)
- [Stock-market-forecasting using time series analysis](https://www.kdnuggets.com/2020/01/stock-market-forecasting-time-series-analysis.html)
