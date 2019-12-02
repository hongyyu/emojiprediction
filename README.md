# Emoji Predictions
### Name: Kyle Wang, Hongyu Li, Lu Wang
Emojis are extensively used and are the evolution of character-based emoticons (Pavalanathan and Eisenstein, 2015). They are powerful for expressing ideas of topics such as food, mood, place, etc. Our goal is to have emoji suggestions when a user is posting a tweet. Currently, emoji can be recommended based on a single word meaning for iMessage. For example, if the user types “pizza”, keyboard will suggest a pizza emoji. According to Emojipedia, the Face With Tears of Joy is the most popular emoji used in 2018. However, this emoji can be interpreted into different meanings such as amusement or embarrassment based on the context. Many emoji has been constantly evolved across cultures over time. There is little to no computational model that can understand emoji with whole content (Barbier et al., 2018). Researching the connection may help sentiment analysis and NLP tasks such as information retrieval (Novak et al., 2015). Moreover, using emoji as a query for searching content that doesn’t contain emoji could be very powerful.

## Included Files

### DataScraping and Cleaning
**data_grab.py** - Used for scraping real-time tweets and could be setted to different emoji for searching if tweets including the specific emoji.\
**adding_label.py** - After saving the real-time tweets to local machine, we transforming each emoji into specific number and remove emoji in each tweet, adn remove all non-English tweets in our dataset.\
**data_clean.py** - Used this step to clean and remove all unexpected characters, stopping words, and punctuations. Meanwhile, we exclude the tweets with words count less than 5.

### Modeling

** Each file (python or jupyter) is one modeling


## Reference Library
#### tweepy - https://tweepy.readthedocs.io/en/latest/
#### Keras - https://keras.io/
#### fastText - https://fasttext.cc/
#### textblob - https://textblob.readthedocs.io/en/dev/
#### preprocessor - https://pypi.org/project/tweet-preprocessor/
#### nltk - https://www.nltk.org/
#### seaborn - https://seaborn.pydata.org/
#### xgboost - https://xgboost.readthedocs.io/en/latest/


