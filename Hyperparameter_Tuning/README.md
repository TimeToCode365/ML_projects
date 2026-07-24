# Hyperparameter Tuning of SVM using Mobile Price Classification Dataset

## Objective

Apply supervised learning to classify mobile phone price categories using a Support Vector Machine (SVM) model and optimize its performance by tuning important hyperparameters using Grid Search, Random Search, and Bayesian Optimization.

## Dataset

Dataset: Mobile Price Classification Dataset (Kaggle)

- Contains mobile phone specifications and their corresponding price categories
- Problem type: Multiclass Classification
- Target variable: `price_range`
- Classes:
  - 0 → Low cost
  - 1 → Medium cost
  - 2 → High cost
  - 3 → Very high cost
- Features: 20 numerical attributes including:
  - Battery power
  - RAM
  - Internal memory
  - Screen dimensions
  - Processor details
  - Connectivity features

The dataset is suitable for SVM as the features are numerical and require scaling before training.

## Steps

- Load and explore the Mobile Price Classification dataset
- Separate input features and target variable (`price_range`)
- Split data into training and testing sets using stratified sampling
- Apply feature scaling using StandardScaler
- Train a baseline SVM model using the RBF kernel
- Evaluate the baseline model performance
- Perform hyperparameter tuning using:
  - Grid Search with cross-validation
  - Random Search with cross-validation
  - Bayesian Optimization using Optuna
- Tune important SVM hyperparameters:
  - C (regularization parameter)
  - Gamma (kernel influence)
  - Kernel type
- Compare optimization methods based on:
  - Model performance
  - Execution time
- Select the final optimized SVM model
- Evaluate the final model using classification metrics

## Results

- Successfully classified mobile phones into different price categories using SVM
- Improved model performance through hyperparameter optimization
- Compared multiple optimization strategies and analyzed their computational efficiency
- Used cross-validation to obtain reliable performance estimates
- Evaluated the final model using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
- Visualized confusion matrix to understand classification performance across price categories
- Observed the trade-off between optimization accuracy and computational cost

## Skills Demonstrated

- Supervised learning using Support Vector Machines (SVM)
- Hyperparameter tuning and model optimization
- Cross-validation for reliable model evaluation
- Grid Search, Random Search, and Bayesian Optimization
- Feature scaling and preprocessing
- Multiclass classification
- Model performance evaluation using classification metrics
- Computational efficiency analysis of machine learning algorithms
- Data visualization and interpretation of ML results
