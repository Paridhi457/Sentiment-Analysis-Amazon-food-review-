Sentiment Analysis using VADER (Valence Aware Dictionary and Sentiment Reasoner) - Bag of Words Approach
This project implements sentiment analysis using the VADER (Valence Aware Dictionary and Sentiment Reasoner) lexicon combined with a Bag of Words approach in Python. The goal of the project is to analyze the sentiment (positive, negative, or neutral) of amazon food reviews entered by various users 

Overview:
Sentiment analysis is a technique used to determine the sentiment or emotional tone expressed in a piece of text. This project focuses on sentiment analysis using the VADER lexicon, a pre-trained rule-based model specifically designed for sentiment analysis.

The Bag of Words approach is employed to convert the text into numerical representations, enabling sentiment classification. The project provides a Python implementation for performing sentiment analysis on different types of textual data.

Dataset:
For this project, I used a dataset of amazon customer reviews. The dataset contained textual reviews along with corresponding sentiment labels. The data preprocessing step involved cleaning the text, removing stopwords, and tokenizing the text into individual words.

Results and Evaluation:
I firstly did some EDA on the data and imported the nltk library. Then I used some basic nltk concepts to tokenize my data into individual words. Following this I used NLTK's SentimentIntensityAnalyser to get the negative, neutral and positive scores of the text. This used the bag of words approach in which stop words are removed and each word is scored and combined to a total score. This technique was able to successfully provide me the mentioned scores using various sentences that I provided as input, thereby analysing their sentiment successfully. 

Conclusion:
I was able to learn quite a lot using this as it honed my knowledge in EDA, bag of words approach, basics of Natural Language Processing and the various features in Python which can easily analyse the sentiment of any given data 
