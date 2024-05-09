# Assignment-2-Sampling
# Machine Learning Sampling Exploration

This project delves into examining the influence of diverse sampling techniques on the efficacy of machine learning models. Sampling techniques are pivotal in managing imbalanced datasets and ensuring the generalizability of models. Here, we investigate five prevalent sampling methods and assess their impacts on five well-known machine learning models.

# Introduction

Within machine learning, sampling techniques hold significance for handling datasets characterized by class imbalances, skewed distributions, or specific traits that may impact model training and assessment. This project seeks to compare the performance of various machine learning models across a spectrum of sampling strategies.

# Sampling Techniques

Simple Random Sampling
Simple random sampling entails the random selection of a subset of data points without adhering to any specific criteria. It represents a fundamental and widely employed sampling approach.

Stratified Sampling
Stratified sampling ensures that the proportion of each class in the sample mirrors the proportion in the entire dataset. This method proves particularly beneficial in addressing imbalanced datasets.

Systematic Sampling
Systematic sampling involves selecting every k-th element from the dataset following a randomly chosen starting point. It serves as a deterministic sampling method, furnishing a representative sample.

Bootstrap Sampling
Bootstrap sampling entails repeatedly sampling with replacement from the dataset. It is commonly utilized for estimating the distribution of a statistic.

Cluster Sampling
Cluster sampling divides the dataset into clusters and randomly selects entire clusters to constitute the sample. It proves advantageous when the dataset exhibits a natural grouping.

# Machine Learning Models

Random Forest
A versatile ensemble learning technique, Random Forest constructs numerous decision trees during training and outputs the mode of the classes for classification tasks.

Logistic Regression
Logistic Regression is a linear model utilized for binary and multiclass classification, predicting the probability of a sample belonging to a specific class.

Decision Trees
Decision Trees, a non-linear model, recursively partition the data based on features, creating a tree-like structure for classification and regression purposes.

Gradient Boosting
Gradient Boosting, an ensemble learning approach, sequentially constructs a series of weak learners (typically decision trees) and amalgamates them to form a strong learner.

Support Vector Machines
Support Vector Machines, a potent classification algorithm, determine the hyperplane that optimally separates the data into distinct classes.

# Conclusion

Random Forest: All sampling techniques, except Stratified Sampling, yield identical accuracies.
Logistic Regression: Systematic Sampling yields the highest accuracy.
Decision Trees: Both Stratified Sampling and Bootstrap Sampling yield the highest accuracy.
Gradient Boosting: All sampling techniques, except Simple Random Sampling, yield identical accuracies.
Support Vector Machines: All sampling techniques, except Simple Random Sampling, yield identical accuracies, with Bootstrap Sampling yielding the highest accuracy.
