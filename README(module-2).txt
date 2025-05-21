Social Network Ads Classifier Project

Name: Touseef Ahmed

Objective:
Predict whether a user purchases a product based on Age and Estimated Salary using:
- Naive Bayes
- K-Nearest Neighbors (KNN)
- Decision Tree

Dataset Information:
- Dataset: Social_Network_Ads.csv
- Source: https://www.kaggle.com/datasets/rakeshrau/social-network-ads
- Features: Gender (encoded), Age, EstimatedSalary
- Target: Purchased

Preprocessing Steps:
1. Dropped User ID
2. Encoded Gender (0 = Female, 1 = Male)
3. Standardized features (Age, EstimatedSalary)
4. Split data into 75% train and 25% test

Models Used:
1. Gaussian Naive Bayes
2. K-Nearest Neighbors (k=3, 5, 7)
3. Decision Tree (Gini, Entropy)

Evaluation Metrics:
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

Performance Summary:
Model                  Accuracy  Precision  Recall  F1 Score
-----------------------------------------------------------
Naive Bayes            0.89      0.89       0.89    0.89
KNN (k=3)              0.90      0.90       0.90    0.90
KNN (k=5)              0.91      0.91       0.91    0.91
KNN (k=7)              0.89      0.89       0.89    0.89
Decision Tree (Gini)  0.89      0.89       0.89    0.89
Decision Tree (Entropy) 0.90    0.90       0.90    0.90

Conclusion:
- Best model: KNN with k=5
- Highest accuracy and F1 score
- Naive Bayes was fast but slightly less accurate
- Decision Trees effective but risk overfitting
