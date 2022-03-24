# SPAM-EMAIL-DETECTION
A real-time deployed version of our project- https://spam-email-detector-app.herokuapp.com/ 

### This project will classify email data into spam and ham emails. The process of spam filtering focuses on two main levels: the subject and content of the emails.
## Spam-Detector 
A spam identifier utilizing the concepts of machine learning.
Email spam detection is done using machine learning algorithm called Naive Bayes.
The spam detection process goes through a series of following steps:

1. Text Mining:
  * Data collection
  * Data Preparation.
  * Cleansing of Data.
  * Data input and Processing
  * Tokenize the Data and count the word frequency.
  * Compute probabilities.

2. Naive Bayes Classifier Approach:
  * Build the Vocabulary of words by separating SPAM and HAM from training data.
  * Store vocabulary of words in a file.
  * Training the classifier on vocabulary.
  * Evaluate the performance of model on test data.
  * Generate a Confusion and Evaluation Matrix.
  

## Evaluation Matrix
* Accuracy: <img src="https://latex.codecogs.com/svg.latex?\frac{TP&plus;TN}{TP&plus;TN&plus;FP&plus;FN}" title="\frac{TP+TN}{TP+TN+FP+FN}" />
* Recall : <img src="https://latex.codecogs.com/svg.latex?\frac{TP}{TP&plus;FN}" title="\frac{TP}{TP+FN}" />
* Precision: <img src="https://latex.codecogs.com/svg.latex?\frac{TP}{TP&plus;FP}" title="\frac{TP}{TP+FP}" />
* F1-Measure: <img src="https://latex.codecogs.com/svg.latex?\frac{2*Recall*Precision}{Recall&plus;Precision}" title="\frac{2*Recall*Precision}{Recall+Precision}" />
## Confusion Matrix

Considering SPAM as a positive class(1) and HAM as the negative class(0):

|                  | Predicted(0)    | Predicted(1)   |
|------------------|-----------------|----------------|
| Actual(0) |       TP = 862      |        FN = 8       |
| Actual(1) |       FP =  1       |       TN = 268      |
