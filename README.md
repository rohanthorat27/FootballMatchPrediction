Football match result classification
A comparison of six different multiclass classification models for prediction of English Premier League matches.

Summary
This notebook exhibits a comparison between the following models implemented through scikit-learn on datasets that provide the match statistics for 10 seasons in the English Premier League.
  Logistic regression
  Random Forest Classifier
  Artifical Neural Network
  Decision Trees Classifier
  Naive Bayes
  K_Nearest Neighbour Classifier
  
About the data
The original datasets consists of 22 usable features and the records of 381 matches per season.

Upon performing exploratory analysis on the data, it was observed that there were two main types of feature transformations required: ordinal and nominal.

The following steps were carried out in order to bring the data into usable format:

Performing one-hot-encoding on the nominal categorical and string features to convert them into multiple features with binary values and ordinal-encoding on the ordinal data to convert string data into multiclass values.

Split the data in 75:25 ratio for training and testing.
