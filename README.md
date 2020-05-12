# Sentimental Analysis of tweets about US Airlines 

Sentiment Analysis is a branch of Natural Language Processing (NLP) that allows researchers to determine whether a statement or document is “positive” or “negative”. It helps organizations to identify trends in public opinion, customer's needs, or brand position by analyzing social media content. 

This project develops several Machine Learning (ML) models to classify the sentiment of tweets regarding USA airlines service and analyze the performance of those models to provide insights about best practices.

## Getting Started

This README.md file provides a description of the process applied to develop ML models to compute the sentiment of text information. 

### Prerequisites

To run this jupyter notebook, ensure you have installed:
```
!pip install numpy
!pip install pandas
!pip install lxml
!pip install beautifulsoup4
!pip install sklearn
!pip install nltk
!pip install wordcloud
```

### Datasets
Two data sets are used in this project:

```
"generic_tweets.txt" file contains tweets that have had their sentiments already analyzed and recorded as binary values 0 (negative) and 4 (positive).

```
Description: 

0 class the polarity of each tweet (0 = negative emotion, 4 = positive emotion).
1 id the id of the tweet (e.g. 2087).
2 date the date of the tweet (e.g. Sat May 16 23:58:44 UTC 2009).
3 query the query (e.g. lyx). If there is no query, then this value is NO_QUERY.
4 user the user that tweeted (e.g. robotickilldozr).
5 text the text of the tweet (e.g. Lyx is cool).

```
"US_airline_tweets.csv" contains a list of tweets regarding several US airlines. It is comma-separated file.

```
Description:

0 id the id of the tweet.
1 sentiment can be “positive” or “negative”.
2 negative_reason reason for negative tweets. Left blank for positive tweets.
3 user the user that tweeted.
4 retweet_count number of retweets.
5 text the text of the tweet.


Both datasets have been collected directly from the web, so they may contain html tags, hashtags, and user tags.


### Research question

What can public opinion on Twitter tell us about the US airlines in 2015?

### Notebook structure


The jupyter notebooks includes:

A. Data Cleaning

B. Exploratory Analysis

C. Text Mining 

D. Model Preparation

E. Model Implementation

F. Discussion of results

