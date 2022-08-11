# Logistic-SGD-Regression-vs-Hinge-Loss-SGD-Regression

For the MNIST dataset, given a digit j ∈ 0, 1, . . . , 9  we create the classification labels to be
1 if the target digit is j or else 0 for the digit j = 5. For each j:

• We compare the performance of Logistic SGD Regression and Hinge Loss SGD binary
classifiers. As a performance measure we use the ’F1’ score of 3−fold cross_val_predict

• For each of the 10 datasets we compare the ROC and P-R curves of each of the four
optimal classifiers we obtained in the previous part. We then discuss whether the best classifier is the same
or are some classifiers best performing for some target variables vs others
