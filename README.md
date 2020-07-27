# Sentiment-Analysis
Having provided with some synthetic (fake, semi-randomly generated) twitter data we build a sentiment classifier, which will detect how positive or negative each tweet is.

# Problem Statement
We have provided some synthetic (fake, semi-randomly generated) twitter data in a csv file named project_twitter_data.csv which has the text of a tweet, the number of retweets of that tweet, and the number of replies to that tweet. We have also words that express positive sentiment and negative sentiment, in the files positive_words.txt and negative_words.txt.

Your task is to build a sentiment classifier, which will detect how positive or negative each tweet is. You will create a csv file, which contains columns for the Number of Retweets, Number of Replies, Positive Score (which is how many happy words are in the tweet), Negative Score (which is how many angry words are in the tweet), and the Net Score for each tweet. At the end, you upload the csv file to Excel or Google Sheets, and produce a graph of the Net Score vs Number of Retweets.

# Function Description
## 1. strip_punctuation:
It takes one parameter, a string which represents a word, and removes characters considered punctuation from everywhere in the word.
## 2. get_pos:
It takes one parameter, a string which represents one or more sentences, and calculates how many words in the string are considered positive words.
## 3. get_neg:
It takes one parameter, a string which represents one or more sentences, and calculates how many words in the string are considered negative words.
## 4. Sentiment Analyser:
It will detect how positive or negative each tweet is. It also produces a csv file called resulting_data.csv, which contains the Number of Retweets, Number of Replies, Positive Score (which is how many happy words are in the tweet), Negative Score (which is how many angry words are in the tweet), and the Net Score (how positive or negative the text is overall) for each tweet.

# Results:
It consists of the final resulting_data.csv file and also a scatter plot of Number of retweets on X-axis and Net score on Y-axis.
