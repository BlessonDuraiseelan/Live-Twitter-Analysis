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




   ![image](https://user-images.githubusercontent.com/76935226/140599362-a0a7176b-abb7-462d-aeda-26aff2cfdf47.png)           ![87276097-dd011780-c49c-11ea-980f-6b27e617faad](https://user-images.githubusercontent.com/76935226/140599299-224e4406-cf76-47c4-bb68-c6ee31d00099.png)

![image](https://user-images.githubusercontent.com/76935226/140599325-3d3673c7-49ba-493d-ad72-fc346d7e4b20.png)

# Check out the App
https://twitterdetails.herokuapp.com/

# About the App
The app provides a section to the user to input the topic to get the results and there are various options provided that will give inssight such as cleaned tweets dataframe, plots for verified accounts and image showing positive and negative tweets. 

![Screenshot (144)](https://user-images.githubusercontent.com/76935226/140599517-cbbbf8c3-adf2-489a-9f23-533b392ef46d.png)
![Screenshot (145)](https://user-images.githubusercontent.com/76935226/140599532-62ac7721-eb4f-4c17-85c9-d4e592eaa346.png)
![Screenshot (146)](https://user-images.githubusercontent.com/76935226/140599542-8aa4071c-1921-41b3-925a-fd833c009a79.png)
![Screenshot (147)](https://user-images.githubusercontent.com/76935226/140599566-564c136b-2548-442f-81f1-72a70ebf8744.png)

















