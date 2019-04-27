
# An empirical analysis to quantify the long-term relationship between Google Trends, Twitter Volume and Bitcoin Price


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

Consequently, the network effect of giant social media platforms provide a valuable channel for prediction in various fields, for example, Shi (2012) used Twitter volume to predict US primary elections, Ranco (2015) utilized Twitter to predict stocks returns, and Dergiades (2018) also estimated tourists’ arrivals statistics using Google Trends. 

However, previous studies that analyzed relationships between digital currency price and web search and discussion indexes are rather limited. Kristoufek (2013) studied the relationship of Bitcoin and search query frequency on Google Trends and also Wikipedia, using series data from May 2011 to June 2013, finding that the increased interest in the Bitcoin currency measured by the searched terms increases its price. Matta (2015) explored the effect of sentiment analysis of tweets related to Bitcoin and its price between January 2015 and March 2015, and suggested that positive tweets may contribute to predict the movement of Bitcoin’s price in a few days.

Although previous work proved the significant social network spreading effect on Bitcoin price, they merely consider this relationship particularly in the short term (less than two years). Moreover, their data is outdated and does not contain time period when Bitcoin price experienced most dramatic fluctuation between 2017 to 2018. Therefore, this report focuses on the long-term relationship between people’s interest in Bitcoin and its correspond price changes, especially during the period when the price of Bitcoin fluctuated sharply.


## 3. Research Idea



Twitter volume indicates the global discussion trends and interests on Twitter, and the Google Trends measures the query frequency and statistics of certain key words within one period by analyzing global searching behaviors. This report aims to quantify the long-term relationship between Internet social media trends, namely Twitter Volume and Google Trends of Bitcoin, and the Bitcoin price. 

In this case, this report attempts to provide a way for predicting Bitcoin price under the context of Internet social media information interaction in the long run.


![bitcoin price](https://github.com/Yeeejlin/PHBS_BlockChain_2018/blob/master/bitcoin%20price.png)
(Data source: [coinmarketcap.com](https://coinmarketcap.com/currencies/bitcoin/historical-data/?start=20150101&end=20190425))

![twitter-volume-daily](https://github.com/Yeeejlin/PHBS_BlockChain_2018/blob/master/twitter-volume-daily.png)
(Data source: Bloomberg L.P.-Twitter volume-topic-Bitcoin)

![Daily Bitcoin Twitter Volume and Price](https://github.com/Yeeejlin/PHBS_BlockChain_2018/blob/master/Daily%20Bitcoin%20Twitter%20Volume%20and%20Price.png)



![twitter-volume-weekly](https://github.com/Yeeejlin/PHBS_BlockChain_2018/blob/master/twitter-volume-weekly.png)
(Data source: Bloomberg L.P.-Twitter volume-topic-Bitcoin)

![Weekly Bitcoin Twitter Volume and Price](https://github.com/Yeeejlin/PHBS_BlockChain_2018/blob/master/Weekly%20Bitcoin%20Twitter%20Volume%20and%20Price.png)


![google trends](https://github.com/Yeeejlin/PHBS_BlockChain_2018/blob/master/google%20trends.png)
(Data source: [Google Trends](https://trends.google.com/trends/explore?q=bitcoin&geo=US))

![Weekly Bitcoin Google Trends and Price](https://github.com/Yeeejlin/PHBS_BlockChain_2018/blob/master/Weekly%20Bitcoin%20Google%20Trends%20and%20Price.png)



