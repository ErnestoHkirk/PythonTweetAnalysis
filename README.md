## Twitter Sentiment Analysis Tool
![chrome_2019-10-29_14-55-13](https://user-images.githubusercontent.com/37064367/67812331-2d922b00-fa5c-11e9-8eb4-60b50e9d79d2.png)
Python program that analyzes the sentiment of a tweet placing it into one of three categories; positive, negative, or neutral.

## How does it work?


## Set-Up Requirements 

1. This program requires you to use a [twitter development account](https://developer.twitter.com/en/apply-for-access.html) in order to access their api which will allow you to fetch the tweets from the user you are analyzing. 
2.  After your account has been created and approved, you will be able to use the keys provided for you in order to access twitters api.
* TWITTER_CONSUMER_KEY
* TWITTER_CONSUMER_SECRET
* TWITTER_ACCESS_TOKEN_KEY 
* TWITTER_ACCESS_TOKEN_SECRET
3. You will need to [create an AWS account](https://docs.aws.amazon.com/general/latest/gr/aws-sec-cred-types.html) to use the [Amazon Comprehend](https://docs.aws.amazon.com/comprehend/latest/dg/how-sentiment.html) api.
* AWS_ACCESS_KEY
* AWS_SECRET_KEY
4. Import the following libraries into your project's interpreter
* PLOTLY
* BOTO3
* PYTHON-TWITTER
5. Enter the required keys you gathered from the steps above. 
6. Enter the twitter username of the account's tweets you wish to analyze, and change the number of recent tweets you wish to analyze. The default is fifty, but you can analyze up to two hundred tweets every call.  
