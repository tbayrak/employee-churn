# Sequential & Non-Sequential Model Benchmarking

Implemented by Musa Berat Bahadır & Ahmet Tuğrul Bayrak

In this notebook, various models for predicting churning employees using Employee Attrition dataset were built. As a different approach from the other implementations, both sequential and non-sequential models were built with their ensemble models. Besides, the evaluation metrics for the minor class are calculated to be able to see if the models are successful or they just favor the major class (which commonly occurs with imbalanced datasets). The parameters for the models were determined via grid search. Apart from that, the k-fold cross-validation is applied for estimating the performance of the models.

The sequential models : LSTM, GRU, Sequential Ensemble

The non-sequential models : Decision Tree, Random Forest, K-Nearest Neighbors, Support Vector Classifier, Logistic Regression, Multilayer Perceptron, Non-Sequential Ensemble

According to the results, Random Forest is the most successful one after the Non-Sequential Ensemble model when considering both classes. Due to the small amount of data, sequential models are not the best ones. The dataset does not have many features, but the approach can be used as preliminary work for more complicated employee churn models.
