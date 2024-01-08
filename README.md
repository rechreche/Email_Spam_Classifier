# Email_Spam_Classifier
Adaboost algorithm is a supervised classification technique' Theorem with an assumption of independence among predictors.

It is a popular technique for text categorization, judging documents as belonging to one category or the other (such as spam or legitimate, sports or politics, etc.) with word frequencies as features.

Goal: Previously unseen records should be assigned a class as accurately as possible

We have a bunch of emails classified as 'spam' and a bunch of emails classified as 'ham' (not spam)
The emails are first read and stored in a dataframe. They are then parsed using CountVectorizer
This information is used to train the model and its prediction is then tested with a sample input
Python Libraries used: pandas, numpy, io, os, CountVectorizer and MultinomialNB from sklearn

The Spam classifier classifies the given input as a spam/ham
