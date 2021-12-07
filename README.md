# Sentiment-Analysis-Experimentation
This is just a personal experiment, where i am trying to Use various methods of performing sentiment analysis. I'm trying to use the famous libraries and their low level functions. The dataset consists of extracted "Top Comments" of a youtube video.

The dataset uploaded has around 199 comments i scraped, the notebook has the code for scraping too
Till now i have tried:
- TextBlob (on cleaned data)
- NRClex (on cleaned data)
- VADER SentimentIntensityAnalyser (on cleaned & uncleaned data) (My favorite one so far)

### Model directory:

I'll be training a model That classifies tweets into +ve or -ve. 

The dataset for training, I chose “Sentiment140”, which originated from Stanford University. 

More info on the dataset can be found from the link. http://help.sentiment140.com/for-students/.

The dataset can be downloaded from the below link. http://cs.stanford.edu/people/alecmgo/trainingandtestdata.zip

- DataCleaning.ipynb: Pre cleaning of data.
