# spring-2023-cis5681-sentiment
Sentiment Analysis process using Twitter developer API:
The main objective of the assigment is to scrape data from twitter using tweepy and perform sentiment analysis on the scrapped tweets to get the public opinion about a certain topic.  NLTK has been used to preprocess the text and classify it as positive, negative, or neutral with the help of TextBlob.
At first, we need to scrape data from twitter. To do this we need a Twitter developer account. Further, you will require NLTK, Tweepy and Wordcloud installed to code along. 
1.	Install the required libraries
2.	Import the required modules
3.	Set up Authentication to connect to Twitter API which we accomplish by creating an authentication object using OAuth.
4.	Search twitter for tweets related to your analysis topic “searchTwitter” function
5.	Convert Tweets into data frame
6.	Clean the data by removing special characters and hyperlinks
7.	Create ”Corpus” of data using word cloud library
8.	Stem the data by removing the punctuations, converting to lower case, strip white spaces, removing stop words
9.	Build the word cloud to see words that are frequently used
10.	Get the sentiment of the tweets and scores
11.	Plot  the sentiment scores 
