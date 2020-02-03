# logistic-regression-variable-selection
Use logistic regression to predict default events. We first discretize the continuous variables, then encode them with one hot code. Finally, we use RFE in the sklearn library to select the variables and get 11 significant features. Finally, the precision, recall and F1 score of 0.75 + are obtained on the test set.
