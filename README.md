 
# Financial-Fraud Detection Model 

## Overview
This project aims to detect financial fraud by employing various machine learning and deep learning models. The dataset includes transactional data with features like transaction type, amount, and balance changes. The objective is to develop models that can accurately classify transactions as fraudulent or non-fraudulent.


Link to the dataset: [Synthetic Financial Dataset](https://www.kaggle.com/datasets/ealaxi/paysim1)

## Dataset
The dataset used in this project consists of transactional data containing the following features:
- Transaction type (e.g., debit, credit)
- Transaction amount
- Balance changes
- Other relevant transaction details

## Methodology
### Preprocessing
- Data cleaning: One-hot encoding and data normalization.
- Feature engineering: Dropping irrelevant features.

### Model Selection
The project explores both traditional machine learning models and deep learning architectures for classification:
#### Machine Learning Models:
1. Logistic Regression
2. Decision Tree
3. K-Nearest Neighbors (KNN)
4. Random Forest
5. Naive Bayes
6. XGBoost

#### Deep Learning Models:
1. Convolutional Neural Network (CNN)

### Model Training and Evaluation
- Splitting the dataset into training and testing sets.
- Training each model using the training data.
- Evaluating model performance using metrics such as accuracy, precision, recall, and F1-score.
- Comparing the performance of different models to identify the most effective ones for fraud detection.

## Results
- Among the machine learning models, the Random Forest classifier demonstrated the best performance based on evaluation metrics.
- Within the deep learning models, the Convolutional Neural Network (CNN) showed promising results for fraud detection.
- Detailed analysis and interpretation of model performance, including confusion matrices and ROC curves.

 
 
