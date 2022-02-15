# Twitter-Sentiment-Analysis

Libraries used here:- Numpy, Pandas, NLTK(Natural Language Tool-Kit for natural language processing of tweets), sklearn (for model training and testing), seaborn and matplotlib for plotting 

Size of dataset is too big to upload here so please use this link to access dataset
Dataset:- https://www.kaggle.com/kazanova/sentiment140

Process flow
![image](https://user-images.githubusercontent.com/84174934/154078351-60abe3be-f8e1-436f-bc71-99456fccd78c.png)


Data Preprocessing :- Here we have reduced tweets into format so that we can fetch the features i.e tweets in a format which can be used for training and testing.
Steps involved:-

a) Removing Html Entities

b) @user from tweets

c) Expanding apostrophe words and short forms

d) Replacing emoticons with positive or negative word

e) Converting tweets to lowercase.

f) Removing punctuations and special characters and numbers from tweets.

g) Removing words of size 1

h) Tokenizing tweets.

i) Applying Lemmatizing to tweets.


Feature Extraction using count vectorizer in sklearn library.

Split the data in ratio of 95:5%.Here, we trained our application over only 400 thousand tweets only where 200 thousand were positive and negative tweets.

Training and Testing using Sklearn.

Results:-

![image](https://user-images.githubusercontent.com/84174934/154079646-87eb975b-db28-48f9-8b8b-8147938d5e83.png)

![image](https://user-images.githubusercontent.com/84174934/154079685-d3536670-aaa4-42dd-af91-a8d1403db3fa.png)
