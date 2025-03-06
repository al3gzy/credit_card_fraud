# Credit Card Fraud Prediction

## Introduction
This project aims to predict fraudulent credit card transactions using machine learning algorithms. The focus is on identifying patterns in transaction data that indicate fraudulent activity. The dataset consists of features such as transaction amount, user information and transaction time, which are used to train a predictive model. The goal is to classify transactions as either fraudulent or legitimate.

## Features
- **Data Preprocessing**: The first step is to clean the dataset by handling missing values, removing outliers and normalizing the features. Feature selection techniques are applied to identify the most important attributes related to fraud detection.

- **Model Selection**: Several machine learning models, including Logistic Regression, Random Forest and Gradient Boosting, are trained on the dataset. Cross-validation is performed to evaluate the model's performance and select the best algorithm based on accuracy, precision, recall and F1 score.

- **Feature Engineering**: New features may be created from the existing dataset to enhance the model's ability to distinguish between fraudulent and legitimate transactions. This may include the creation of interaction terms or aggregation of certain features.

- **Train-Test Split**: The dataset is split into training and testing sets. The model is trained on the training set and its performance is evaluated on the test set using metrics like accuracy, precision, recall and F1 score.

- **Model Evaluation**: The models are evaluated using confusion matrices, ROC curves and AUC scores to determine how well they distinguish between fraudulent and non-fraudulent transactions. The performance is compared across different models.

## Results
After training and evaluating the models, it is found that Random Forest and Gradient Boosting yield the highest performance, with an F1 score of 95%. The confusion matrix reveals a high true positive rate, indicating that the models effectively identify fraudulent transactions. The model's accuracy and recall show that it can detect fraudulent activities with high precision.
