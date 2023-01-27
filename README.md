# Coronavirus-Tweet-Sentiment-Analysis

Predicting sentiment of COVID-19 tweets

#What is sentiment analysis?

Sentiment Analysis is the method of 'computationally' defining if a piece of writing is positive, negative or neutral. It’s also known as opinion mining, deriving the opinion of a presenter.

#Why sentiment analysis?

Business: In marketing field companies use it to develop their strategies, to understand customers’ feelings towards products or brand, how people respond to their campaigns or product launches and why consumers don’t buy some products.

#Problem Description

This challenge asks you to build a classification model to predict the sentiment of COVID-19 tweets.The tweets have been pulled from Twitter and manual tagging has been done then. The names and usernames have been given codes to avoid any privacy concerns. You are given the following information:

1.Location
2.Tweet at
3.Original Tweet
4.Label

#Approach

![158756264-a379e4fd-1732-4267-999c-33b1d4783d98](https://user-images.githubusercontent.com/31198822/215026965-012055c5-e0c1-4a86-92cc-ec58468da718.png)

1.Familiarized and cleaned the data by doing preliminary analysis, and dealt with null values performed EDA.

2.Removed html tags and unwanted words from the text data. Tokenization and stemming functions are applied.

3.Extracted hashtags belonging to different classes.

4.Used count vectorization for vectorizing the tweet text.

5.implemented multiple classification models for multi class classification.


#Technologies

1.Python

2.NLTK

3.Textblob

4.Pandas

5.Google Colab

6.Seaborn

7.Matplotlib

#Result

I built a classification model that predicts the sentiment of tweets with an accuracy score of 78%.
