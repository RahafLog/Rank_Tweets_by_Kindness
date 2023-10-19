# Sentiment Analysis from Tweets
**Sentiment Analysis**: Social media can be a great place to connect with others and share positive thoughts and experiences. However, it can also be a breeding ground for negativity and hate speech. This project aims to develop a system to rank tweets by kindness in order to promote more positive and supportive online interactions.

**Benefits:**

The proposed system has the potential to provide a number of benefits, including:

- Promoting more positive and supportive online interactions
- Reducing the spread of negativity and hate speech
- Helping people to find and connect with others who share their values
- Making social media a more enjoyable and welcoming place for everyone


**Tasks:**

The proposed system will use sentiment analysis to identify and rank tweets based on their level of kindness. This will be done by the following steps:

1. Read the `nice_words.txt` file into a list. This file will contain a list of words that are typically associated with kindness, such as "love," "compassion," and "gratitude."
2. Read the tweets list. 
3. Look at each of the tweets and count the number of nice words.
4. Sort the tweets in descending order based on the number of nice words, with the most kind tweet first.
5. Display the tweets, along with the count of nice words in each tweet.
6. Use Sentiment Analysis

*****
**Tools** :

***NLTK:*** The Natural Language Toolkit, commonly known as NLTK, is a comprehensive open-source platform for building applications to process human language data.It comes with powerful text processing libraries for typical Natural Language Processing (NLP) tasks like cleaning, parsing, stemming, tagging, tokenization, classification, semantic reasoning, etc. NLTK has user-friendly interfaces to several popular corpora and lexical resources Word2Vec, WordNet, VADER Sentiment Lexicon, etc. 
We use the SentimentIntensityAnalyzer class to assign a sentiment score to each tweet the tweets that we get from Twitter API.
Also, we used the polarity_score method of the SentimentIntensityAnalyzer class to generate a numeric score in the range of
negative one (-1) to positive one (+1) to indicate the intensity of how negative or positive the sentiment is.

The three sentiment type values are.
- neg for negative sentiment
- neu for neutral sentiment
- pos for positive sentiment
- compound for an overall score that combines negative, positive, and neutral sentiments into a single score.


***The RapidAPI:*** 
The RapidAPI is a platform that allows developers to access and integrate various APIs (Application Programming Interfaces) into their applications. 
These APIs provide a range of functionalities and data from different sources, including Tweets.
By using the RapidAPI, we easily retrieved *Tweets of users* and performed sentiment analysis using the SentimentIntensityAnalyzer. 
The API can provide a convenient way to access the reviews and pass them to the sentiment analysis tool.
*****

