# Spam_classifier

This is one of the projects I work on as I follow Aurelien Geron's Hands-On Machine Learning with Scikit-Learn, Keras and TensorFlow, Copyright 2019 Aurélien Géron, 978-1-492-03264-9. You can get yourself a copy of the book [here](https://www.amazon.com/Hands-Machine-Learning-Scikit-Learn-TensorFlow/dp/1491962291).

The goal of the project is to make a Spam Classifier that is capable of classifying emails as spam or ham (binary classification), with both high recall and high precision. We will use examples of spam and ham from Apache SpamAssassin's public datasets(https://homl.info/spamassassin).

## Project overview

  * Download and understand the data format
  * Perform exploratory data analysis
  * Split the data into training and test sets
  * Prepare the data using pipelines:
  * Train and evaluate a few models on recall, precision :
      *  Logistic Regression
      *  Decision Trees
      *  Random Forest
      *  Random Forest
   * Fine-tune and combine the best classifiers (Random Forest and Logistic Regression)
   * Evaluate on the test set

 ## Performance Boost
   * Cross Validation  
   * Grid Search 
   * Voting Classifier

## Results 

After trying many models, tuning them and combining, we see that all of our models are performing excellent, but without a doubt, **the combined Random Forest + Logistic Regression** is the best, with a **100% precision and 96.84% recall**.


## Code and Resources Used 
**Python Version:** 3.7  
**Packages:** pandas, numpy, sklearn, email, scipy, urlextract, nltk
**Aurelien Geron's Hands-On Machine Learning with Scikit-Learn, Keras and TensorFlow:** https://github.com/ageron/handson-ml2
