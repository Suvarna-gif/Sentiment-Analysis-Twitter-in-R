# Sentiment-Analysis-Twitter-in-R
Twitter Sentiment Analysis project in R
Takes feeds from Twitter into R. The sentiment of the tweets is analysed and classified into positive, negative and neutral tweets.

Pre-requisites
Installation of R (Version 3.3.1)
Twitter Authentication to access API
Dependencies
twitteR
stringr
ROAuth
RCurl
ggplot2
reshape
tm
RJSONIO
wordcloud
gridExtra
plyr

Steps for Execution
Short Version -
The codes are compiled into one file script_running.R.

Longer Modular Version-
For easier understanding, the above code is modularized and must be learnt in following order-
The following are for lexical based twitter analyzer (Tweets to find sentiment about entities):

authentication.R
tweet_extraction.R
Word Database.R
cleaning_data.R
emoticon.R
score_sentiment.R
func_on_tweet.R
graphs.R
Percentage.R
level_of_sentiment.R
Frequent hastags of user.R
Top tweeters and timeline of particular hashtag.R
wordcloud.R
For any further queries and difficulties that you face on executing any code, feel free to post it under the issue tab above and we will get back to you as soon as possible.
