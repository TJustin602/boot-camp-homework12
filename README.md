# Unit 12—Tales from the Crypto

![Stock Sentiment](Images/sentimental.jpeg)

## Background

There's been a lot of hype in the news lately about cryptocurrency, so you want to take stock, so to speak, of the latest news headlines regarding Bitcoin and Ethereum to get a better feel for the current public sentiment around each coin.

In this assignment, you will apply natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. You will also apply fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

Complete the following tasks:

1. [Sentiment Analysis](#Sentiment-Analysis)
2. [Natural Language Processing](#Natural-Language-Processing)
3. [Named Entity Recognition](#Named-Entity-Recognition)

---

### Files

[Starter Notebook](Starter_Code/crypto_sentiment.ipynb)

---

### Instructions

#### Sentiment Analysis

Use the [newsapi](https://newsapi.org/) to pull the latest news articles for Bitcoin and Ethereum and create a DataFrame of sentiment scores for each coin.

Use descriptive statistics to answer the following questions
#
#  Questions:

#### Q: Which coin had the highest mean positive score?

#### A: Bitcoin has the higher mean positive score (0.089) compared to Bitcoin (0.041).

#### Q: Which coin had the highest compound score?

#### A: Based on the descriptive statistics, Ethereum has the highest compound score at 0.87 vs. the maximum compound score of 0.81 from Bitcoin.

#### Q. Which coin had the highest positive score?

#### A: Ethereum has the highest positive score at 0.31 maximum  compared to 0.20 maximum received by Bitcoin.
![btc-sent.jpg](Images/btc-sent.jpg)
![eth-sent.jpg](Images/eth-sent.jpg)
#
# Natural Language Processing

In this section, you will use NLTK and Python to tokenize the text for each coin. Be sure to:

1. Lowercase each word
2. Remove punctuation
3. Remove stop words

Next, look at the ngrams and word frequency for each coin.

1. Use NLTK to produce the ngrams for N = 2.
2. List the top 10 words for each coin.

Finally, generate word clouds for each coin to summarize the news for each coin.

![btc-word-cloud.png](Images/btc-word.jpg)

![eth-word-cloud.png](Images/eth-word.jpg)

#### Named Entity Recognition

In this section, you will build a named entity recognition model for both coins and visualize the tags using SpaCy.

![btc-ner1.jpg](Images/btc-ner1.jpg)
![btc-ner2.jpg](Images/btc-ner2.jpg)

![eth-ner1.jpg](Images/eth-ner1.jpg)
![eth-ner2.jpg](Images/eth-ner2.jpg)
![eth-ner3.jpg](Images/eth-ner3.jpg)



---

### Resources

[Vader Sentiment Analysis](http://www.nltk.org/howto/sentiment.html)

---

### Hints and Considerations

The free developer version of the News API limits the total monthly requests, so be careful not to exceed the free limits.

---

### Submission

* Create Jupyter Notebooks for the NLP analysis and host the notebooks on GitHub.

* Include a Markdown that summarizes your homework and include this report in your GitHub repo.

* Submit the link to your GitHub project to Bootcamp Spot.

---

© 2020 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
