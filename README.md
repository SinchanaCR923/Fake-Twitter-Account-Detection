#FAKE TWITTER ACCOUNT DETECTION

This project is aimed to detect fake Twitter accounts using machine learning techniques. We used Twitter API to collect data from Twitter, and then extracted features from every tweet to feed to the classifiers. After running several classifiers, we found that binary classification through the Support Vector Machine (SVM) is the most efficient way to detect fake Twitter accounts.

##Dependencies:

Python 3
Scikit-learn
Tweepy


##Usage:

Set up a Twitter developer account and create a new app to obtain API credentials (consumer key, consumer secret, access token, and access token secret).
Open config.py and enter your API credentials.
Run data_collection.py to collect data from Twitter. You can specify the number of tweets to collect and the keywords to search for.
Run feature_extraction.py to extract features from the collected data.
Run classification.py to run different classifiers and compare their performance. The final conclusion is that binary classification through the SVM is the most efficient way to detect fake Twitter accounts.



##Conclusion
In this project, we have demonstrated that binary classification through the SVM is more efficient than through any other classifier in detecting fake Twitter accounts. By using machine learning techniques and Twitter API, we have built a framework that can be used to detect fake Twitter accounts in real-time.

We hope that this project can be used as a starting point for further research in this field.
