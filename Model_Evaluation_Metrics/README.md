# Evaluation Metrics - Pick the Best Performer

## Objective
Evaluate and compare multiple pretrained machine learning models on a test dataset to identify the best-performing model using appropriate evaluation metrics.

## Dataset
- Test data: `iris dataset` from scikit-learn
- Pretrained models: `model1_decision_tree.pkl`, `model2_logistic_regression.pkl`, `model3_knn.pkl`, `model4_svm.pkl`, `model5_random_forest.pkl`

## Steps
1. Load the test dataset using **pandas**.
2. Load each pretrained model using **joblib**.
3. Use each model to make predictions on the test set.
4. Evaluate model performance:  
   - **Classification models:** accuracy, precision, recall, F1-score  
5. Compare all models based on the evaluation metrics.
6. Identify the best-performing model and provide reasons for selection.
7. Handle preprocessing consistency (scaling, encoding) between training and testing.
8. Ensure model type matches the dataset type (classification vs regression).
9. Handle exceptions if a model fails to load or predict.

## Results
- Evaluation scores for each model (accuracy, precision, recall, F1 for classification)
- Best-performing model selected based on metrics
- Observations and analysis summarized in the notebook

## Skills Demonstrated
- Loading and evaluating pretrained models using **joblib** and **pandas**
- Applying classification and regression evaluation metrics
- Critical comparison and selection of ML models
- Ensuring preprocessing consistency and handling exceptions
