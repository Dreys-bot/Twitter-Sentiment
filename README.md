# Analyzing Twitter Users
### A sentiment Analysis Project using Python

This project was done using Natural Language Processing Techniques. The purpose of this application is to know the feelings of people from the tweets collected. Since Twiiter receives thousands of tweets per day, I just had to find a way to collect them. Python libraries such as Pandas (for data cleaning/manipulation), NLTK (Natural Language Toolkit), MatPlotlib and WordCloud (for data mining), Plotly (for some data visualizations) were used for this project.

In the [ Jupyter Notebook ](https://github.com/Dreys-bot/Twitter-Sentiment/blob/main/twitter_sentiment_.ipynb), you will learn how I carried out the following steps for the project:

1. Import Librairies
2. Tweets Mining
3. Data Cleaning
4. Location Geocoding
5. Tweets Processing
6. Data Exploration
7. Sentiment Analysis

![alt text](https://github.com/Dreys-bot/Twitter-Sentiment/blob/main/steps.png)

## Tweets Processing Steps
To reach the ultimate goal, there was a need to clean up the individual tweets. To created a function "remove_pattern" and "hashtag_tweet" to remove punctuation, symbols and stop word from the tweets in a single run. I also created a concept known as "tokenized_tweet" in NLP. It is a method of splitting a sentence into smaller units called "tokens". A simple demonstration is show below:

![alt text](https://github.com/Dreys-bot/Twitter-Sentiment/blob/main/twist1.png)
## Word Cloud Generation
To get the most common words used in the tweets, I made use of the POS-tag module in the NLTK library. Using the wordCloud library, one can generate a word Cloud based on word frequency and superimpose these words on any image. In this case, I used Matplotlib to display the image. The wordCloud show the words with higher frequency in the bigger text size while the "not-so" common words are in smaller text sizes.

![alt text](https://github.com/Dreys-bot/Twitter-Sentiment/blob/main/wordcloud.png)
## Visualizing Most Common Words
The plot below was generated using Plotly Library for Python.

![alt text](https://github.com/Dreys-bot/Twitter-Sentiment/blob/main/statistics1.png)
![alt text](https://github.com/Dreys-bot/Twitter-Sentiment/blob/main/statistics2.png)

## Sentiment Analysis
For this analysis, I created a linear model "LogisticRegression()". To measure the accuracy of my model, I used an accuracy_score function. But the use of probability makes my model even more accurate. Thus, for a probability higher than 0.3, the comments are positive if not they are negative.

![alt text](https://github.com/Dreys-bot/Twitter-Sentiment/blob/main/result.png)
For this results, we conclude that the tweets are negatives.

## Remarks
the result was not surprising because the arrival of COVID-19 was very devastating for the whole world

## Credits
Made from the video [ Twitter Sentiment Analysis using Python](https://www.youtube.com/watch?v=RLfUyn3HoaE)
