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

<img width="1461" alt="8cb5b6c0e1fe4e4ebfd30b769204c0d30c332fec" src="https://user-images.githubusercontent.com/76935226/140599162-d2ecbff8-dcf4-4626-8abc-5dc5504d3360.png">

(https://user-images.githubusercontent.com/76935226/140599189-f8a1f0e6-2257-4189-8193-0133eead5c91.png)










