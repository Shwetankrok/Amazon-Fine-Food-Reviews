# Amazon-Fine-Food-Reviews
Predict Food Reviews as Positive or Negative 

OBJECTIVE: Given any food review text should predict whether the review as Positive or Negative.

<br>About Project: </br>

Contains Sqlite file where food reviews of Amazon from 1999 to 2012 are there.

<br> Due to file size issue I can't upload sqlite file here but you can download the file <br>
<br> Link to download the data and Sqlite file </br>

# Amazon Fine Food Reviews Analysis


Data Source: https://www.kaggle.com/snap/amazon-fine-food-reviews <br>


# Objective:
### Given a review, determine whether the review is positive (Rating of 4 or 5) or negative (rating of 1 or 2)

The Amazon Fine Food Reviews dataset consists of reviews of fine foods from Amazon.<br>

Number of reviews: 568,454<br>
Number of users: 256,059<br>
Number of products: 74,258<br>
Timespan: Oct 1999 - Oct 2012<br>
Number of Attributes/Columns in data: 10 

Attribute Information:

1. Id
2. ProductId - unique identifier for the product
3. UserId - unqiue identifier for the user
4. ProfileName
5. HelpfulnessNumerator - number of users who found the review helpful
6. HelpfulnessDenominator - number of users who indicated whether they found the review helpful or not
7. Score - rating between 1 and 5
8. Time - timestamp for the review
9. Summary - brief summary of the review
10. Text - text of the review

</b>

# Data
https://www.kaggle.com/snap/amazon-fine-food-reviews/kernels

### Task Performed: 

<br>
<b>1.Reading the data from SQLite and filtering (taking into consideration) only Score which are 1, 2 ,4 and 5 ignoring Score with 3.</b></br>
<br><b>2.Changing the value of Score column such that Score of 1 and 2 are 0 ( Negative) while Score of 4 and 5 are 1 (Positive).</b></br>
<br><b>3.Removing duplicate entries or error rows.</b></br>
<br><b>4.Creating a function to clean the text i.e. review given by removing punctuations, stopwords etc.</b></br>
<br><b>5.Taking the cleaned text as input(independent variable) and Score(0 or 1) i.e. positive or negative as dependent variable.</b></br>
<br><b>6.Splitting the data and uses CountVectorizer to get counts of words frequency in text (review) Column.</b></br>
<br><b>7.Build Multinomial Naive Bayes Classifier with Count Vectorizer(Bag of Words) to predict reviews using Hyperparameter Tuning.</b></br>
<br><b>8.Use Logistic Regression Classifier to predict whether the review was positive or negative using Hyperparameter Tuning.</b></br>
<br><b>9.Built Multinomial Naive Bayes Classifier with TFIDFVectorizer to predict reviews with Hyperparameter Tuning.</b></br>
<br><b>10.Built Decision Tree Classifier with TFIDFVectorizer to predict reviews with Hyperparameter Tuning.</b></br>
<br><b>11.Built Random Forest Classifier with TFIDFVectorizer to predict reviews with Hyperparameter Tuning.</b></br>
<br><b>12.Built XgBoost Classifier with TFIDFVectorizer to predict reviews with Hyperparameter Tuning.</b></br>
<br><b>13.Built LSTM classiifer using pretrained glove vectors to predict reviews with Hyperparameter Tuning.</b></br>
<br><b>14.Evaluated all models with various metrics like Accuracy, Precision, Recall and F1-Score.</b></br>
<br><b>15.Summary all models performance scores and conclusion.</b></br>
https://www.kaggle.com/snap/amazon-fine-food-reviews/kernels





