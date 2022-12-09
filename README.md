# Twitter Sentiment Analysis
Authors: Anita Camlic, Dermot O'Brien, Dermot Holcombe
______________________________________________________________________________________________________
## Overview 
Apple wants to be able to understand their users. Since product reviews can have bias, we turned to Twitter. Twitter is a public service for friends, family, and coworkers to communicate and stay connected through the exchange of quick, frequent messages. People post Tweets, which may contain photos, videos, links, and text. These messages are posted to your profile, sent to your followers, and are searchable on Twitter search. 
We are using a dataset with tweets from the 2016 South by Southwest music festival. These tweets are labeled by sentiment (Positive, Neutral, Negative). Each row in the data provides relavant information about the content in each tweet. We used this dataset along with natural language processing techniques to predict tweet sentiment about Apple products and the brand itself.  

## Business Problem

The Apple Product team is constantly looking for changes they can implement to keep users happy. We were asked by Apple's Product team to create a model that can predict the sentiment of a tweet based on it's content. This model will categorize tweets as either positive or negative.

After the tweets are categorized, the Apple Product team can take a look at our words/bigrams with the highest TF-IDF average, and use that to inspire changes in certain products. Or, they can take a look at the negative tweets and the direct complaints that users are making on Twitter. These complaints and statements can then be used to make informed changes to products that users are unhappy about. This model will act as a general filter for finding tweets to provide insight on places of improvement.

In turn, this will allow Apple to better serve their users. It will give them the opportunity to make changes to products, that will hopefully decrease the amount of complaints and increase the positive viewpoints of the Apple and it's products.

## Data Overview

The original dataset contains 3 columns titled 'tweet_text', 'emotion_in_tweet_is_directed_at', and 'is_there_an_emotion_directed_at_a_brand_or_product'. The column 'tweet_text' contains individual tweet content as a string and was renamed 'tweet' for easier understanding. The column 'emotion_in_tweet_is_directed_at' contains strings representing the subject that the tweet is discussing and was renamed 'subject' for simplification. The column 'is_there_an_emotion_directed_at_a_brand_or_product' contains strings representing the percieved emotion being conveyed in the tweet. This column was renamed for 'emotion' for simplification.  

## Methods 
We used multiple classification algorithms to learn from our dataset and classify new tweets as having either positive or negative sentiment. The final model we agreed upon was a Random Forest model with tuned hyperparameters.

## Results
Our model was created to predict tweet sentiment about Apple products and the brand itself. We chose the metric accuracy. Our final recall score was 88 percent. This means that our model, when ran on unseen data, predicted the observation's true class correctly 98 percent of the time.

This model will benefit the business if put to use because it will flag negative and positive tweets about Apple. Using these insights can help Apple to change and improve their current products as well as improve user's outlooks This model is extremely powerful and can be very beneficial to the Apple Product Team.

## Conclusion

### For More Information

______________________________________________________________________________________________________

