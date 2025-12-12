# Breast-Cancer-Diagnosis-Prediction
A machine learning project for predicting whether a breast tumor is benign or malignant using the Breast Cancer Wisconsin Dataset.

# Project overview
The goal is to classify breast cancer tumors as Malignant (1) or Benign(0) using machine learning techniques:
- Data cleaning
- Encoding
- Min max Normalization
- Train/Test spliting
- K-Nearest Neighbors (KNN) Classifier
- K-Means Clustering (Unsupervised Learning)
  
# Data Processing
- Encoding diagnosis column
     - M → 1 (Malignant)  
     - B → 0 (Benign) 
- Removing unused columns
      - id 
      - Unnamed: 32
  
# Scaling features with Min-Max Normalization
In the breast cancer dataset, Min-Max Normalization scales all the feature values into a fixed range, usually 0 to 1. 

# Split the Dataset
Split data into:
-80% Training Data
-20% Testing Data

# K-Means Clustering (k = 2)
- Performed clustering to group data into two clusters  
- Compared clusters with actual diagnosis labels

# Train KNN Classifier (k = 5)
-Trained to predict tumor type based on feature similarity

# Model Evaluation
Evaluated using the following metrics:
     - Accuracy
     - Precision
     - Recall
     - F1-Score





