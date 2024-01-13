# Time Series Classi cation Part 1: Feature Creation/Extraction

An interesting task in machine learning is classi cation of time series. In this problem,
we will classify the activities of humans based on time series obtained by a Wireless
Sensor Network.

In Part 1, use logistic regression models for binary classification. Features are extracted from time series data obtained from a Wireless Sensor Network, focusing on time-domain features. The features include minimum, maximum, mean, median, standard deviation, first quartile, and third quartile for each of the six time series in each instance. Bootstrapping is used to estimate the standard deviation of these features. The three most important time-domain features are selected using judgment, and logistic regression is employed for binary classification.

In Part 2, binary classification is further explored using logistic regression. Scatter plots of selected features are depicted to distinguish between bending and other activities. The time series are broken into segments, and logistic regression is applied to each segment. Cross-validation is used to determine the optimal number of features and the best value for the parameter "l." Confusion matrices, ROC curves, and AUC are reported for the logistic regression classifier on the training data, and the classifier is tested on the test set. Imbalanced classes are addressed, and a logistic regression model based on case-control sampling is built.

Additionally, L1-penalized logistic regression is introduced in Part 2(b) to compare with variable selection using p-values. Multi-class classification is tackled in Part 2(c) using L1-penalized multinomial regression and Naïve Bayes' classifier with Gaussian and Multinomial priors. The best parameter "l" is determined using cross-validation, and test error is reported. The definitions of confusion matrices and ROC curves for multiclass classification are explored.

Overall, logistic regression plays a central role in both parts for binary classification, and additional techniques such as L1-penalization and Naïve Bayes' classification are introduced for further analysis.

Problem Statement in Homework3.pdf