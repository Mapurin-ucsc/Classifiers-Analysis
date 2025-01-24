# Comparing Classifiers
## Overview
As part of this analysis of a dataset detailing a bank's marketing campaigns from UCI's Machine Learning Laboratory, we were tasked with constructing several AI models that exercised several key techniques to provide the most optimal approach for marketing that our clients should take to generate the most significant revenue stream.
## Models created
After deconstructing the dataset to find the most important data, which we found to be the number of positive responses from the clients, we then used that as the target variable and trained models using Logistic Regression, KNN, Decision tree, SVM. We found that the most effective models were the Logistic models in our initial testing with a test accuracy of 91.1%, which was trailed closely by the KVM model which had a test accuracy of 90.8%. Curiously, we had a training accuracy of 100% for the decision tree model but found that it performed the worst out of all the models, likely due to overfitting. Additionally, we found that the training time for the SVM models was significantly higher than the remainder of the models at 8.63 seconds compared to under a second for the other models.
## Recommendations
Following our rigorous testing, we recommend our clients use the Logistic Regression or the KVM model.
