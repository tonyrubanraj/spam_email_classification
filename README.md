# Spam email classification
A python project to train a logistic regression learning algorithm in identifying spam emails.

There are various supervised learning algorithms that can be used for classification problems. One of the applications of these learning algorithms is classifying spam emails. In the current analysis, a Logistic Regression is used to classify the mails. The email data used for the analysis is obtained from the spamassassin website (https://spamassassin.apache.org/old/publiccorpus/).

## Steps
1. Download and extract the email data from spam assassin
2. Process the mail content to only words by removing unnecessary characters and replacing URLs, emails, amount and numbers
3. Tokenize the processed mail content and identify frequency of words in each mail
4. Use the top 5000 frequent words and perform feature extraction (i.e 5000 words as features with their count in each mail)
5. Train the learning algorithm
6. Predict the output

## Results
Precision :  0.9094955489614244\
Recall :  0.9863234111021721\
F1 score :  0.9463527595522965\
Accuracy score :  0.9608229988726043

## Libraries used
* urllib
* tarfile
* re
* copy
* glob
* email
* sklearn
* numpy
* pandas
