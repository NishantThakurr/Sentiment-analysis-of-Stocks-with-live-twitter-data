
# Sentiment analysis of Stocks with live twitter data

The task was to fetch current 10 stocks which have gained highest and lost highest 
Webscraping was done on moneycontrol website.

2)Using web scraping top 10 gainers and losers were fetched

3)Using a twitter api,tweets refering to these stocks were fetched
and sentimental analysis was done using textblob library.

4)Various graphs were plotted to analyse the proportion of positive and negative tweets.



# Hi, I'm Nishant Thakur! 👋

I am a engineer by qualification who is highly curious about numbers and data.I have a warm enthusiasm for converting data to some useful insights and models.


## Roadmap


1)Web Scraping

Top 10 gainers and losers from Bombay Stock Market was fetched 
with the help of python libraries such as 'requests' and 'Beautiful Soup'.

The sites that were used for web scraping were https://www.moneycontrol.com/stocks/marketstats/bseloser/index.php
 and https://www.moneycontrol.com/stocks/marketstats/bsegainer/index.php

2)Creating a class Twitter with a constructor and several methods inside it
 such as get_tweets which is used to fetch and parse tweets,preprocessing which is used to clean tweets and get_tweet_sentiment which is used to get sentiment of the tweets using a textblob library which uses a lexicon based approach.

3)Creating a function sentimentalanalysis which return positive tweets percentage,negative tweets percentage an neutral tweets percentage for a particular stock.

4)Creating separate dictionaries to store the top ten company names along with their positive and negative tweet percentage.

5)Creating several bar plots for further analysis.
## Screenshots

![sentimentanalysis1](https://user-images.githubusercontent.com/102639991/180588788-a93221d7-60d9-41f9-ab2c-c32d43e23cb3.png)
![Semanticanalysis2](https://user-images.githubusercontent.com/102639991/180588799-40735029-a504-488a-8568-3c9cd99bf448.png)




## Improvements

There are many Improvements that can be done to fetch better results.

They are:

1)Facebook,Instagram and social media sentiments can also be fetched.

2)News headlines can also be fetched.

3)Instead of using textblob many machine learning models can also be used for a better classification of positive and negative tweets.
## Disclaimer

Various tokens such as customer_key,acess_token has been hidden for security.
If you wish to run these code by yourself please log in to twitter develepor account and generate these tokens.