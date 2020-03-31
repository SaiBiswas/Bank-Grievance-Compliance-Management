# Bank Compliance Management Classification
This is a Text Mining Project on Bank Data Compliance Management System. Generally, the consumer grievances against Banks broadly fall into two categories; “Un-fair and deceptive business practice related (UFDP)” and “efficiency related (not UFDP)”.
It is expected that the Bank monitors compliance management system on a regular basis to “self-identify weaknesses and take corrective action” by closing grievance (irrespective of type of grievance) with or without monetary relief etc.  Similarly, where grievance is closed with explanation, resulting in a potential dispute, it is expected that “consumer grievance response” is measured in terms of effectiveness of communication. 

# EDA Steps Taken

1. Checking the basic information related to the train as well as the test data.
2. Checking the basic statistics related to the train as well as test data.
3. Checking the word count in the train as well as test data.
4. Calculating the number of words in the train.
5. Calculating the number of characters in each line of the train & test data.
6. Checking the number of stopwords in the train as well as test data.
7. Checking the number of Special characters in the train as well as test data.
8. Removing Punctuation from the train as well as test data.
9. Checking the number of upper case words in both the train and test data.
10. Rare words removal for the train and test data.
11. Checking the frequency of rare words in the train and test data.
12. Removing special characters for both train and test data.

# Feature Engineering

1.Lemmatization( The process of converting a word to its root form from the Whole Dataset)
2.Generating N grams for the train and test data.
3.Constructing TFIDF matrix to check the number of weight of important words in the matrix.
4.Checking the feature names for the train and test data.
5.Since the train data is quite large, generated 2 clusters that contains the TFIDF values for the whole text.
6.Standardizing both the train & test data.
7.Label Encoding and Fitting the transformed data both on train and test.



# Modelling

1. Logistic Regression yielding an an accuracy of 50.80% on test data.
2. Random Forest yielding an accuracy of 50.58% on the test data.

# Other Modelling options that could had been implemented

1. Could have tried LSTM to check the incoming next word.
2. RNN to predict the values in the next data.

So, based on the results obtained from the modelling techniques we can select either the Random Forest or the result obtained by the Log reg model as both give us similar accuracy rate.
