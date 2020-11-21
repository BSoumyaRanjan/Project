# Text Classification using Naive Bayes Classifer

# Natural Language Processing
It is a sub-domain of
Artificial Intelligence that is centered around empowering
computers to understand and interpret the human
language. The issue with interpreting the human language
is that it's anything but a lot of decides or paired
information that can be taken care of into the framework
and understanding the setting of a discussion.

# Text Classification
It is a mechanized cycle of characterization of text into
predefined classes. We can
arrange Emails into spam or
non-spam, news stories into
various classes like Politics, Stock
Market, Sports, and so on
This should be possible with the
assistance of Natural Language
Processing and distinctive
Classification Algorithms like
Naive Bayes Classifier and even
Neural Networks in Python.

# DATA 
The SMS Spam collection is a set of SMSs tagged messages that
have been collected for SMS Spam research. It contains one set
of set of SMS messages in English of 55 74 messages, tagged
according being ham (legitimate) or spam. The image below is
the first five rows of the dataset.

# DATA PRE-PROCESSING
The Data contains 5574
initially and removing the
duplicate values, there are
5169 rows.
Below, there are two broad techniques used for data preprocessing:
1. Tokenization:
Tokenization is the method/process used for converting a
text input into smaller parts like words, phrases, symbols, or
other meaningful elements called tokens. NLTK library
uses word_tokenize or sent_tokenize to break a text into
tokens.

2.Word Streaming/Lemmatization:
The main objective of this process is to reduce the inflection
forms of each word into common base/root.

3.Stop Words:
Stop words such as ‘the’
,
’a’
,
‘an’ and etc. which are useless in
natural language processing. The punctuations are also
useless in natural language processing.

# ALGORITHMS

The goal of this project is to study the classificational data and forecast
the probability of different classes based on various attributes.
This project uses Naïve Bayes Classifier and Support Vector
Machine algorithm to predict the classes which is mostly used for text
classification.
It uses Bayes Theorem which predicts the membership probabilities of
each class such as the probability that given record belongs to a
particular class. The maximum probability is considered as the most
likely class.
It also uses Support Vector Machine outputs an optimal hyperplane
which categorizes new examples. In two-dimensional space this
hyperplane is line dividing plane in two parts where in each class lay in
either side.
We have used Train-test-split function in scikit-learn to split the data
into a training set and testing set, it could split the whole dataset into
several packs and in each pack, the indices of the testing set would be
higher than the training set. By doing this can prevent look-ahead bias,
which means the model would not use future data to train itself

# POPULATION EVALUATION METRICS 

# Precision
In a classification problem, precision can be determined
by the number of true positives divided by the total
number of the true positives and false positives.
# Recall
In a classification problem of two classes, recall can be
calculated as the number of true positives divided by the
number of true positives and false negatives.
# F1 Score
The F1 Score is the 2*((precision*recall)/(precision+recall)). It is also called the F Score or the F Measure
# Support
Support can be calculated as the number of samples of
the true response that lie in that class.


# CONCLUSION
Both the algorithms (Support Vector Machine & Naïve Bayes
Theorem) show good results but Support Vector Machine has better
accuracy than Naïve Bayes Classifier.
Accuracy for Support Vector Machine: 98.07%
