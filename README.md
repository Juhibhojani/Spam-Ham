# Spam-Ham

<b>Task</b> : Classifying as Spam-Ham based on texts 
<b>Dataset used</b> : SMS Spam Collection Dataset <br>
<b>Source </b>: Kaggle<br>
<b>URL</b> : https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

# Dataset Metadata <br>
The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged acording being ham (legitimate) or spam.

# Steps performed
1) Importing Neccessary libraries
2) Performing Exploratory Data Analysis
     -> Dropping unneccesary columns <br>
     -> Showcasing Dsitribution of data<br>
     -> Checking for duplicate columns and dropping them <br>
     -> Counting length of each text<br>
     -> Checking for NULL values<br>
     -> Displaying first spam and ham sms<br>
     -> Analysing number of words in each category of sms<br>
3) Data Cleaning<br>
     -> Decode HTML encoded characters<br>
     -> Removing Stop words<br>
     -> Removing URL's and square brackets <br> 
4) Applying Lemmitization 
5) Displaying Word Cloud
6) Label enconding Class 
7) Applying Tf-Idf vectorizer and different models
8) Result

# Libraries used 
1) Pandas
2) Numpy
3) Sklearn
4) NLTK
5) Wordcloud
6) BeautifulSoup
7) Matplotlib


# Models
1) Decision Tree Classifier
2) Random Forest Classifier
3) Logisitic Regression
4) KNN
5) Navie Bayes
6) SVM

# Result:<br>
<br>
As it's an imbalanced dataset, use of accuracy as a metrics isn't appropriate and hence , ROC_AUC score has been used here. We obtain the best results when SVM model is used with a score of 98.19%

