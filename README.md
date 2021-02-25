# NLP Election

Analyzing each candidate tweets and replies they received, to predict 2020 presidential elections 

* Please note beacuse of time limitation on this project, classification algorithum isn't included yet in this project which was initialized on an automatic approach but all sentiment analysis are covered
### This project was build using:


* Liabraries:
  1. TextBlob to analyze sentiment
  2. WorldCloud to visualize data
  3. Pandas to read tweets in dataframe
  4. Matplotlib to visualize data


* Tweepy Installation:

    
      pip install tweepy



* Sign up for Twitter Developer account to generate necessary tokens & keys
![](Images/developer.jpg)
----------------
## [Fetch tweets](Notebooks/FetchTweets.ipynb)

* each candidate: using API feature "user_timeline"
  This feature has a limitation on the number of tweets requested up to 200 maximum.

* replies to each candidate: using tweepy feature "Cursor"
  This feature can iterate through 10,000 tweets per request maximum which will increase our analysis accuracy.




## [Create functions to evaluate Rational & Emotional analysis of each tweet](Notebooks/SentimentAnalysis.ipynb)
* Polarity & Context : to measure Emotional reactions, where 1 is positive, 0 is neutral, & -1 is negative.

* Subjectivity & Tone: to measure Rational reactions, where 0 is objective&  1 is subjective

* Emojis
* Irony and Sarcasm
## Donald Trump tweets were:
- 39.5 % Positive  
- 12.50 % Negative
-  48 % Neutral

-  **140 times** Exclamation Mark was used



![](Images/t_bar.JPG)
![](Images/tcloud.jpg)



## Joe Biden tweets were:
-  50 % Positive
- 18 % Negative
- 32 % Neutral
- Exclamation Mark was used 4 times only.
  
  ![](Images/jbar.jpg)
![](Images/bcloud.jpg)




  
  ![](Images/bse.jpg) ![](Images/bse.jpg)


## Voters' favor Joe Biden over Donald Trump, their replies sentiment analysis shows:

* Positive replies scored 58.76 % for Joe Biden & 47.22 % for Donald Trump
  


* Negative replies scored 41.22 % for Joe Biden & 52.78 % for Donald Trump
  
  





![](Images/compare.jpg)


* Users' replies to Donald Trump tweets
  
![](Images/last.jpg)

* Users' replies to Donald Trump tweets
  
![](Images/last2.JPG)


---------------------------
## References
* [API USER Timeline Limitation](https://stackoverflow.com/questions/46734636/tweepy-api-user-timeline-count-limited-to-200)
* [Regex Cheatsheet](https://www.debuggex.com/cheatsheet/regex/python)
* [TextBlob & sentiment analysis](https://medium.com/@rahulvaish/textblob-and-sentiment-analysis-python-a687e9fabe96)
* [Calculating Polarity and Subjectivity](https://planspace.org/20150607-textblob_sentiment/)
* [Hvae Fun with TectBlob](https://towardsdatascience.com/having-fun-with-textblob-7e9eed783d3f)
* [Twitter Docs-Cursor](https://docs.tweepy.org/en/v3.5.0/cursor_tutorial.html)


