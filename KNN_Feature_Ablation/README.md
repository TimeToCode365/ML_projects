# KNN with Feature Ablation Study

## Objective
Train a K-Nearest Neighbors (KNN) classifier on the Breast Cancer Wisconsin dataset and perform a feature ablation study to identify the most important features.

## Dataset
- Breast Cancer Wisconsin Dataset : `breast_cancer_wisconsin .csv`
- Target column: `diagnosis` (M = 1, B = 0)

## Steps
1. Drop `id` column and encode the target variable
2. Normalize all features
3. Train KNN classifier (k = 5) using train-test split
4. Evaluate model using accuracy, precision, recall, and F1-score
5. Perform feature ablation by removing one feature at a time and retraining

## Results
- Baseline KNN model evaluated on full feature set
- Performance metrics recorded for each ablation step
- Features causing the largest performance drop identified

## Skills Demonstrated
- Data preprocessing and normalization
- KNN classification
- Model evaluation with multiple metrics
- Feature ablation and analysis
