# Custom-Random-Forest-Classifier
The ipython notebook consists of a custom made random forest classifier without the use of sklearn.

Accuracy of custom random forest classifier on the spam data comes out to be 87.75%
The accuracy of sklearn random forest classifier comes out to be 96%. 
The accuracy has been claculated for varying max_features technique.
OOB error decreases as we increase the number of estimators to split the data. The plot for various max_features techniques is shown below. 'log2' and 'sqrt' max_features perform better than splitting with all the features, as the no_of_estimators increase.
The code has been written along with brief comments on what the method/statememt does.
