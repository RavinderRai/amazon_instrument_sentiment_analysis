![Sentiment Analysis image](https://www.altexsoft.com/media/2018/09/sentiment_analysis.jpg)

# Amazon Musical Instrument Sentiment Analysis

Online shopping has revolutionized the way people buy and sell products, and this of course includes instruments. With countless types of instruments and related accessories available on the websites like Amazon, customers rely heavily on product reviews to inform their purchasing decisions. As a result, sentiment analysis has become an increasingly popular tool for businesses to understand customer feedback and improve product offerings. Here we will explore the results of this sentiment analysis project, where we will go over all steps of the data science lifecycle. Of course, the purpose of sentiment analysis is to find valuable insights and the strengths and weaknesses of products, as well as identify areas for improvement, but this is typical and not hard to interpret. Thus, we will focus more on the technical aspects of this project, and show what the best model is in detail, and how it was obtained.

## Data Wrangling and EDA

[Data Wrangling and EDA Notebook](https://github.com/RavinderRai/Amazon_Instrument_Sentiment_Analysis/blob/main/notebooks/Data_Wrangling_and_EDA.ipynb)

The data here comes from kaggle (https://www.kaggle.com/datasets/eswarchandt/amazon-music-reviews/discussion/161304), so data collection was easy. Luckily the only cleaning we really had to do was the typical text cleaning you would do in any NLP project. Aside from that, there were a few other columns in this dataset not usually present in these types of projects, like the helpfullness column. This column gave us some idea on if a review was actually good or not. It seems like in the future perhaps this feature might be useful in building another sentiment analysis model.

Other than that, the most notable thing here was the distribution of the sentiments. There are only three here, namely good, bad, and neutral. As you can see below, the data is quite imbalanced. This was a great challenge here, and the modelling aspect of the project tries to tackle getting a good model to work with this data.


## Pre-Processing and Modeling

[Pre-Processing and Modeling Notebook](https://github.com/RavinderRai/Amazon_Instrument_Sentiment_Analysis/blob/main/notebooks/Pre-Processing_and_Modelling.ipynb)

