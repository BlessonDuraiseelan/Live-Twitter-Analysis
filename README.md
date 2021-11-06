# Live-Twitter-Analysis
This is a Project done for the explanation of NLP Techniques applied in live feed of Tweets.
We are developing a webapp using Tweepy API that will be used to fetch tweets in realtime for the topic entered by the user and use various graphical representation for drawing insights of the tweets and also use NLP Techniques on the collected tweets.

# Model Building

The data is collected with the help of Tweepy API which is enabled by providing the access tokens that will ensure that the connection is established. Then various parameters such as tweet_user , location , time ,Retweets etc  are used which will be used to store the respective information in the columns which will be converted to a dataframe.
Fetched tweets are cleaned by applying various NLP Techniques to obtain the desired insight. There is also provison for the user to download the data.

# Development and Deployment

The developed app gives the user various inputs for the user to apply and see the relative information live. 
The processing happens in real time.
The app has been developed with the help of streamlit and has been hosted on the web by Heroku.




![Heroku](https://user-images.githubusercontent.com/76935226/140599295-0097ce54-79d6-497f-8231-cfcd9e76f0a7.png)

![87276097-dd011780-c49c-11ea-980f-6b27e617faad](https://user-images.githubusercontent.com/76935226/140599299-224e4406-cf76-47c4-bb68-c6ee31d00099.png)














