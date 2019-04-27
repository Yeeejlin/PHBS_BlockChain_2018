
# An empirical analysis to quantify the long-term relationship between Google Trends, Twitter and Bitcoin Price


## 1. Background Introduction


### 1.1 Bitcoin

The concept of Bitcoin was first proposed by Nakamoto on November 2008, and was formally born on January 2009. According to the idea of Satoshi Nakamoto, Bitcoin is a virtual encrypted digital currency in the form of a decentralized payment system called Peer to Peer (p2p) network.

Unlike all currencies, instead of being issued by a specific monetary institution, Bitcoin is generated by a large number of calculations based on a specific algorithm. Bitcoin economy uses a distributed database composed of many nodes in the whole P2P network to confirm and record all transactions, and uses cryptographic design to ensure the security of all links of currency circulation. The de-centralization of P2P and the algorithm itself can ensure that the value of the currency cannot be manipulated artificially by making a large number of bitcoins. Cryptographic design allows bitcoins to be transferred or paid only by real owners in an anonymous way of currency ownership and circulation transactions. The biggest difference between Bitcoin and other virtual currencies is that the total amount of Bitcoin is relatively scarce, whose total number will be permanently limited to 21 million.

### 1.2 The Difference between Bitcoin and Stocks as investment instruments

Bitcoin, who has recently aroused public attention as an investment instrument, is intrinsically different from stocks in financial features. Stocks represent the ownership of a company's assets, which can bring returns to investors. Therefore, as long as the company's performance grows, the value of stocks in investors' share will increase. Even if the stock price falls and the market value evaporates, the corresponding physical assets still exist. However, Bitcoin itself does not create wealth, nor does it correspond to any physical assets, etc. Also, the monetary function of Bitcoin is also virtual, which is different from precious metals such as gold and government credit currency.

Capital speculation is an important driving factor in terms of the fluctuation of digital currency price. Bitcoin prices fluctuate dramatically, which is mainly caused by international and domestic speculation behaviors. Meanwhile, since Bitcoin has no underlying fundamental value, it is impossible to predict the price of Bitcoin in the same way as predicting the stock price based on macro market and company fundamentals. Therefore, ordinary investors face enormous risks when investing in Bitcoins due to the difficulty in predicting its price moving trends.

### 1.3 Twitter Volume and Google Trends

With the popularization of Web media, the Internet is not only a platform to disseminate information but also an interaction platform for users to provide feedbacks via posting, votes, and search behaviors. 

Google, the world's largest search engine company, has reached 1 billion users in 2017, which is one quarter of the total global Netizen (Popper, 2017). Besides, Twitter is one of the most popular social networks worldwide. Part of the appeal is the ability of users to follow any other user with a public profile, enabling users to interact with celebrities who regularly post on the social media site. The Twitter micro-blogging service averaged at 321 million monthly active users at the end of 2018, accounting for 11% of the total world Netizen (Statista, 2019).

![twitter user](https://github.com/Yeeejlin/PHBS_BlockChain_2018/blob/master/twitter%20user.png)

(Data source: https://www.statista.com/statistics/282087/number-of-monthly-active-twitter-users/)

## 2. Literature Review

Consequently, the network effect of giant social media platforms provide a valuable channel for prediction in various fields, for example, Shi (2012) used Twitter Volume to predict US primary elections, Ranco (2015) utilized Twitter to predict stocks returns, and Dergiades (2018) also estimated tourists’ arrivals statistics using Google Trends. 

However, previous studies that analyzed relationships between digital currency price and web search and discussion indexes are rather limited. Kristoufek (2013) studied the relationship of Bitcoin and search query frequency on Google Trends and also Wikipedia, using series data from May 2011 to June 2013, finding that the increased interest in the Bitcoin currency measured by the searched terms increases its price. Matta (2015) explored the effect of sentiment analysis of tweets related to Bitcoin and its price between January 2015 and March 2015, and suggested that positive tweets may contribute to predict the movement of Bitcoin’s price in a few days.

Although previous work proved the significant social network spreading effect on Bitcoin price, they merely consider this relationship particularly in the short term (less than two years). Moreover, their data is outdated and does not contain time period when Bitcoin price experienced most dramatic fluctuation between 2017 to 2018. Therefore, this report focuses on the long-term relationship between people’s interest in Bitcoin and its correspond price changes, especially during the period when the price of Bitcoin fluctuated sharply.


## 3. Research Idea

Twitter Volume indicates the global total discussion trends and interests on Twitter, and the Google Trends measures the query frequency and statistics of certain key words within one period by analyzing global searching behaviors. This report aims to quantify the long-term relationship between Internet social media trends, namely Twitter Volume and Google Trends of Bitcoin, and the Bitcoin price. In this case, this report attempts to provide a way for predicting Bitcoin price under the context of Internet social media information interaction in the long run.

## 4. Data

This report collects data set range from Janurary 2015 to April 2019. 

### 4.1 Bitcoin Price

The Bitcoin price data is obtained from coinmarket.com, from 1st Jan 2015 to 1st Apr 2019. It could be seen that the Bitcoin price continuously increased from Jan 2017 to Dec 2017, reaching the highest point at USD 19497.4 on 16th Dec 2017. After that, jumped off nearly half of the price within 2 months to USD 6955 on 5th Feb 2018, and kept fluctuating in a downward trend since then.

![bitcoin price](https://github.com/Yeeejlin/PHBS_BlockChain_2018/blob/master/bitcoin%20price.png)
(Data source: [coinmarketcap.com](https://coinmarketcap.com/currencies/bitcoin/historical-data/?start=20150101&end=20190425))

### 4.2 Twitter Volume

The Twitter Volume index is accessed from Bloomberg in topic search by key word ‘Bitcoin’. This report collects both daily and weekly Twitter Volume data from 2th Jan 2015 to 24th Apr 2019.

#### Daily Twitter Volume on Bitcoin Topic

![twitter-Volume-daily](https://github.com/Yeeejlin/PHBS_BlockChain_2018/blob/master/twitter-Volume-daily.png)
(Data source: Bloomberg L.P.-Twitter Volume-topic-Bitcoin)

#### Weekly Twitter Volume on Bitcoin Topic

![twitter-Volume-weekly](https://github.com/Yeeejlin/PHBS_BlockChain_2018/blob/master/twitter-Volume-weekly.png)
(Data source: Bloomberg L.P.-Twitter Volume-topic-Bitcoin)

### 4.3 Google Trends

Google Trends measures the heat of the specified content in the current period through the statistics of keyword search Volume over a period of time. Hence, Google Trends can quantify the topic search Volume and fully reflect the most interesting topics around the world. This report collects the Google Trends data on key word 'Bitcoin' in a global range from Jan 4th 2015 to 21th Apr 2019.

![google trends](https://github.com/Yeeejlin/PHBS_BlockChain_2018/blob/master/google%20trends.png)
(Data source: [Google Trends](https://trends.google.com/trends/explore?q=bitcoin&geo=US))

### 4.4 Data Z-Score Standardization

Due to the gap between different variable dimensions, this report standardizes all data in order to improve data comparability and analysis accuracy. 

The main purpose of Z-Score is to transform data of different ranges into the same range, and to measure it with the calculated Z-Score value in order to ensure the comparability of data.

Before standardizing the Z-Score data, it is needed to get the following information:

1) The mean of the total data (μ)
2) Standard deviation of total data (σ)
3) Individual observations (x)

Z-Score = (x-μ)/σ

Then the standardized variables comparisons are as follows:

![Daily Bitcoin Twitter Volume and Price](https://github.com/Yeeejlin/PHBS_BlockChain_2018/blob/master/Daily%20Bitcoin%20Twitter%20Volume%20and%20Price.png)

![Weekly Bitcoin Twitter Volume and Price](https://github.com/Yeeejlin/PHBS_BlockChain_2018/blob/master/Weekly%20Bitcoin%20Twitter%20Volume%20and%20Price.png)

![Weekly Bitcoin Google Trends and Price](https://github.com/Yeeejlin/PHBS_BlockChain_2018/blob/master/Weekly%20Bitcoin%20Google%20Trends%20and%20Price.png)


## 5. Data Analysis

### 5.1 Stationary Test

Since time series data is used to do the regression, the times series data must satisfy the requirement of stationary process. To get a rough inference on the stationary hypothesis, this report draws the time series plot and ACF figures about SCI.

#### (1) Stationary Test on Google Trends

Figure below shows the autocorrelations of Google Trends seem to be statistically significant at every lag level from lag 1 to lag 6. Based on this, this report makes a preliminary hypothesis that “Google Trends” time series are not stationary. 

![1](https://github.com/Yeeejlin/PHBS_BlockChain_2018/blob/master/stationary%20test%20on%20google.png)

Next, ADF test is adopted to verify the hypothesis above. The null hypothesis of ADF test is H0: 
There is unit root in “Google Trends” ADF test. If we cannot reject the null hypothesis, “Google Trends” is a non-stationary time series. Here is the ADF test results: 

![1](https://github.com/Yeeejlin/PHBS_BlockChain_2018/blob/master/unit%20root%20google.png)

From the results above, although the graph is not a classic stationary process, the ADF test proves that the t-statistics value is smaller than the 5% level critical values, so the series “Google Trends” is a stationary process at 5% level.

#### (2) Stationary Test on Twitter 

The autocorrelations of “Twitter-Weekly” seems to be statistically significant at every lag level from lag 1 to lag 6. Similarly, autocorrelation plot with ADF test is also shown in Table 2. The results suggest that t-statistics has a value of -3.257828 smaller than 5% level, indicating that the Null Hypothesis should be rejected and the Twitter weekly data is stationary. By using the same methodology, it is found that “Twitter-daily” data is also stationary. 

![1](https://github.com/Yeeejlin/PHBS_BlockChain_2018/blob/master/stationary%20test%20on%20twitter.png)

![1](https://github.com/Yeeejlin/PHBS_BlockChain_2018/blob/master/unit%20root%20twitter.png)

### 5.2 Cross-Correlation Test

To minimize the effect of collinearity when estimating the regression model, “Google Trends” and “Twitter”, as two independent variables, should be tested for cross-correlation test. If these two independent variables are highly-correlated, a valid Instrument variable measurement should be found or test the impact of each independent variables by constructing several linear regression models with one variable. 

![1](https://github.com/Yeeejlin/PHBS_BlockChain_2018/blob/master/CORR1.png)

![1](https://github.com/Yeeejlin/PHBS_BlockChain_2018/blob/master/CORR2.png)

From the time series plots and cross-correlation result above, “Google Trends” and “Twitter-weekly data” are highly correlated. Thus, this report will construct two regression models that includes one independent variable each time to minimize the impact of collinearity. 

### 5.3 Regression Results

After the processing of data and the test of stationary, this report uses OLS model to study the impact of Google Trends and Twitter Volume on the price of Bitcoin. Two models are constructed as follows:

(1) Price t = β0 + β1 * Google Trends t + e

(2) Price t = β0' + β1' * Google Trends t + e'

#### 1) Regression of Google Trends on Price

![1](https://github.com/Yeeejlin/PHBS_BlockChain_2018/blob/master/regression%20google.png)

The regression results show that Google Trends has a significant and positive coefficient of 0.750459, which means increase of GOOGLE will result in increase of the price of Bitcoin. Besides, Adjusted R-square of the regression is 0.5813, which shows the 58% of the dependent variable can be reasonably explained by Google Trends.

#### 2) Regression of Twitter Volume on Price

![1](https://github.com/Yeeejlin/PHBS_BlockChain_2018/blob/master/regression%20twitter.png)

Regression results show that Twitter also has a positive coefficient of 0.750459 and it is statistically significant, which means increase of Twitter Volume will result increase of the price of Bitcoin. Besides, Adjusted R-square of the regression is 0.5823 here, indicating that 8% of the dependent variable can be explained by the Twitter Volume.

### 5.4 Heteroscedasticity Test

This part will test whether the residual of regression models has the characteristics of homoscedasticity. The test of heteroscedasticity is to ensure that the regression parameter estimator has good statistical properties. If the linear regression model has heteroscedasticity, the traditional least squares method is used to estimate the model, and the obtained parameter estimator is not a valid estimator, or even an asymptotically effective estimator. Under this circumstance, it is impossible to significantly compare the model parameters. And this report use the White test and Breusch-Pagan-Godfrey test and judge whether the residual has homoscedasticity and our estimators are valid.

#### (1) Heteroscedasticity test on model (1)

![1](https://github.com/Yeeejlin/PHBS_BlockChain_2018/blob/master/Heteroscedasticity%20test%20google.png)

Table 5 shows the result of heteroskedasticity test results on e. The p value of F-statistics and Chi-square statistics are 0.0923, 0.0836 and 0.1522 respectively, they are all larger than 0.05, which means the residual of our regression model obey the homoscedasticity. The result of Breusch-Pagan-Godfrey Test suggests similar result. The p value of F-statistics and Chi-square statistics are all larger than 0.05, which is consistent with White test. Therefore, the residual of this model follows the homoscedasticity and the regression model (1) is valid.

#### (2) Heteroscedasticity test on model (2)

![1](https://github.com/Yeeejlin/PHBS_BlockChain_2018/blob/master/Heteroscedasticity%20test%20twitter.png)

According to the result of White test in Table 6, p value of F-statistics and Chi-square statistics are larger than 0.05, which means the residual of our regression model obey the homoscedasticity. The result of Breusch-Pagan-Godfrey Test shows similar result. The p value of F-statistics and Chi-square statistics are all larger than 0.05, which is consistent with White test. It can be concluded that the residual of model (2) also follows the homoscedasticity. 









