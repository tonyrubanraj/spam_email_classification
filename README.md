# spam_email_classification
A python project to compare various learning algorithms in identifying spam emails

There are various supervised learning algorithms that can be used for classification problems. One of the applications of these learning algorithms is classifying spam emails. Here, various learning algorithms are used to classify the mails and their results are compared. The email data used for the analysis is obtained from the spamassassin website (https://spamassassin.apache.org/old/publiccorpus/).

## Steps
1. Download and extract the email data from spam assassin
2. Process the mail content to only words by removing unnecessary characters and replacing URLs, emails, amount and numbers
3. Tokenize the processed mail content and identify frequency of words in each mail
4. Use the top 5000 frequent words and perform feature extraction (i.e 5000 words as features with their count in each mail)
5. Train the learning algorithms
6. Predict the output and compare results

## Algorithms used in the analysis
1. SVC
2. Decision Tree
3. Random Forest
4. Logistic Regression
5. MLP

## Results
Though all 4 evaluation metrics namely f1 score, accuracy, precision and recall are displayed, we are choosing f1 score as the primary metric.
SVC - 0.54
Decision tree - 0.94
Random Forest - 0.96
Logistic regression - 0.96
MLP - 0.96
