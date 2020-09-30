# COVID19_PRIMO


# README #

This README would normally document the content of the Comvest website. 

![Alt text](./images/logo.png)


### What is this repository for? ###

* Quick summary
* Version
* [Learn More about i-sip](http://i-sip.encs.concordia.ca/)


### Materials Covered Here ###
- [About the Project](#about)
- [COVID19 PRIMO](#COVID19-PRIMO)
- [Figure Discription](#figure-discription)


## About The Project
A full dataset on the Dow Jones market price and the related tweets from 2016 to 2020. 
A real dataset is incorporated to evaluate performance of the proposed COVID19-DSMP framework, which illustrates superior performance in comparison to its recently developed counterparts.


## COVID19 PRIMO

* the COVID19 PRIMO dataset is constructed based on the Dow Jones stock market index and its associated Tweeter messages for the period of 01/01/2016 to 30/07/2020 is introduced.
 
* Here, we consider the stock movement prediction problem as a binary classification task based on the adjusted closing price.
 
* The focus is on the problem of stock price movement prediction as close observation of market movements can reveal presence of a significant amount of trading targets with minor movement ratios.

* For the news component of the COVID-19 price movement prediction dataset, we focused on Twitter. Fig. 1 shows the block diagram of the appraoch followed to collect and analyze Twitter messages. Web scraping from the Twitter search engine is utilized to build the Twitter dataset. The official API of the Twitter has some limitations that limits the extent of text that can be extracted. Additionally, the official API of the Twitter cuts the tweets at times, which in turn results in items with missing data. We have developed a localized API to address the aformentioned issues. The localized API uses Twitter search engines and directly collects the required dataset from Twitter. We set up our data collection platform based on scraping the twitter website. The twitter web scraping returns the tweet text content with a range of useful attributes, for example, T weet − ID, Tweet Created at, Retweet, Text, Favorite Count, Hashtag Text, User ID, Followers Count, Friends Count, Statuses Count, User Created at and location. To have more precious information of public tweets, we added a constraint to our implementation to collect tweets retweeted more than once. Many other unnecessary attributes regarding a tweet were also removed from the data gathering session to focus on the essential information such as date, tweet text, and the retweet number. Fig. 2 illustrates an illustrative example of raw tweets collectted by web scraping. 
 


## Figure Discription
    
