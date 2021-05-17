# Tasks:

Do twitter streaming analysis using Spark streaming

Train machine learning algorithms to perform sentiment analysis based on the training data and classify stream of tweets using Spark MLib

Store the fetched tweets data and their classification results in a database

# You will need to:

Register on Twitter Apps

Go to https://developer.twitter.com/en/apply-for-access.html and apply for a twitter developer account. 

Login at https://apps.twitter.com/ 

Click “Create New App”, fill out the form, and click “Create your Twitter application”. For the Website URL, you can put any URL here. You only need to fill in all the required places. 

On the next page, click on the “API keys” tab, and copy your “API key” and “API secret”. 

Scroll down and click “Create my access token”, copy your “Access token” and “Access token secret”. 


# Training data could be obtained from here:

https://docs.google.com/file/d/0B04GJPshIjmPRnZManQwWEdTZjg/edit


# With the following format:

The data is a CSV with emoticons removed. Data file format has 6 fields:

0 - the polarity of the tweet (0 = negative, 2 = neutral, 4 = positive)

1 - the id of the tweet

2 - the date of the tweet

3 - the query. If there is no query, then this value is NO_QUERY.

4 - the user that tweeted

5 - the text of the tweet
