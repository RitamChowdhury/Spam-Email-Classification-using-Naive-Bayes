# Spam-Email-Classification-using-Naive-Bayes

Spam messages in our emails are really annoying . I've tried to implement an automated method using maching learning tool to Filter emails and predict wether its spam or real email using Naive Bayes.

Naive Bayes is a supervised classification technique based on Bayes' Theorem with an assumption of independence among predictors. That is, a Naive Bayes classifier assumes that the presence of a particular feature in a class is unrelated to the presence of any other feature.

It is a popular technique for text categorization, judging documents as belonging to one category or the other (such as spam or legitimate, sports or politics, etc.) with word frequencies as features.

# Goal: Previously unseen records should be assigned a class as accurately as possible

* We have a bunch of emails classified as ['spam']

and a bunch of emails classified as ['ham']
(not spam)

* The emails are first read and stored in a dataframe. They are then parsed using CountVectorizer

* This information is used to train the model and its prediction is then tested with a sample input

* Python Libraries used:*  

pandas, numpy, io, os, CountVectorizer and MultinomialNB from sklearn
