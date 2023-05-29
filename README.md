# DBScan-clustering
In this problem, you are asked to play with some datasets and get more familiar with DBScan clustering algorithm hyperparameters:

a) Load each of the given datasets and plot them. Based on your observation, discuss the count of clusters in each dataset and outliers.

b) Implement the DBScan function with the below template:
DBScan(X_train, Epsilon, MinPoints) -> labels : list(its length is equal with X_train)

c) With sufficient tries and using the above function, cluster each dataset and plot the clusters (each with unique color).

d) Implement the function below, which makes it possible to predict new samples based on obtained clusters:
DBScanPredict(x_train, dbscan_cluster_labels, x_sample) -> predicted label for x_sample
Describe your strategy for assigning cluster labels based on DBScan.

e) For each dataset, split it into 85:15 train and test sets. Predict the test samples using DBScanPredict based on obtained clusters via the DBScan. Report the accuracy, discuss results, and plot test samples to indicate that assigned to which cluster.(with colors)

f) Now, train the 3-NN and 5-NN models for each data set with the above situation, calculate accuracy, and compare results with the previous part. Which one is better? Why? Justify your answers.
