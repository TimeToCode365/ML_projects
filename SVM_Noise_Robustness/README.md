# SVM Noise Robustness Study

## Objective
Evaluate the performance and robustness of a Support Vector Machine (SVM) classifier under varying levels of noise, to understand how data corruption affects model accuracy.

## Dataset
- Red Wine Quality dataset: `redwinequality.csv`  
- Features include chemical properties of wines (e.g., acidity, sugar, pH)  
- Target: Wine quality rating

## Steps
1. Preprocess the dataset (handle missing values, normalize features)  
2. Implement SVM classifier using scikit-learn  
3. Gradually inject Gaussian/random noise into feature values  
4. Retrain the SVM at each noise level and evaluate using metrics like accuracy, precision, recall, and F1-score  
5. Visualize performance metrics vs. noise level to identify the breakdown point  
6. Document observations on model robustness and sensitivity

## Results
- SVM model trained and evaluated under multiple noise levels  
- Identified threshold where performance deteriorates sharply  
- Visualizations show impact of noise on model accuracy and reliability  

## Skills Demonstrated
- Support Vector Machine implementation with scikit-learn  
- Data preprocessing and feature normalization  
- Noise injection experiments and robustness testing  
- Model evaluation and performance visualization  
