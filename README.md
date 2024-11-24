# Credit-Card-Fraud-Detection-A-Dive-into-Machine-Learning-Model-Performance-and-Sampling-Techniques
This repository delves into the application of machine learning to identify fraudulent credit card transactions. By leveraging a dataset of anonymized transactions, the project explores various techniques, including Logistic Regression, Random Forest, Gradient Boosting, Support Vector Machines, Neural Networks, and Isolation Forest.
data set on kaggle - visit https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

# About Dataset
Context
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

Content
The dataset contains transactions made by credit cards in September 2013 by European cardholders.
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
# Features
Dataset: The project utilizes anonymized transactional data with labeled instances of fraudulent and legitimate transactions.
Data Preprocessing: Includes cleaning, normalization, and splitting of data into training and testing sets.
Feature Engineering: Emphasis on reducing data dimensionality and selecting the most impactful features for the detection models.
Machine Learning Models: Implementation of multiple algorithms to compare performance, including:
Logistic Regression
Random Forest
Gradient Boosting
Support Vector Machines
Neural Networks
Evaluation Metrics: Models are evaluated using metrics like accuracy, precision, recall, F1-score, and ROC-AUC to ensure robust performance.
Insights and Interpretability: Discussion on model interpretability, identifying key variables contributing to fraud detection.
 # Goals
Detect fraudulent transactions with high accuracy.
Minimize false negatives to avoid missing fraudulent activities.
Optimize computational efficiency for scalable implementation.
Results
The project showcases a systematic approach to fraud detection, achieving significant improvement in identifying fraud while maintaining a low false positive rate. A comparative analysis of algorithms is included to highlight trade-offs between interpretability and performance.

