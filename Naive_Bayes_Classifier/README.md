# Naive Bayes Text Classification from Scratch

## Objective
Implement a Naive Bayes classifier from scratch using NumPy and compare it with Scikit-learn's implementation for spam email classification.

## Dataset
Dataset: Spam Email Classification Dataset

- Contains email messages labeled as **ham** or **spam**
- Features:
  - Email text
  - Class label
- Total samples: 5171 emails
- Classes:
  - Ham (legitimate emails)
  - Spam (unwanted emails)
- Text data is converted into word-based features for classification

## Steps

1. Load and explore the spam email dataset
2. Preprocess email text and create word-based features
3. Implement Multinomial Naive Bayes from scratch using NumPy
4. Calculate:
   - Prior probabilities
   - Word likelihood probabilities
   - Posterior probabilities using Bayes' theorem
5. Apply Laplace smoothing to handle unseen words
6. Train Scikit-learn's MultinomialNB model for comparison
7. Evaluate both models using:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Confusion matrix

## Results

- Successfully classified emails into spam and ham categories using Naive Bayes
- Scratch implementation achieved **97% accuracy**
- Scikit-learn implementation achieved similar performance with **97% accuracy**
- Compared custom and library implementations to validate the correctness of the algorithm

## Skills Demonstrated

- Naive Bayes classification
- Bayes theorem and conditional probability
- Text preprocessing and feature extraction
- Laplace smoothing
- Binary classification
- Model evaluation and comparison
- NumPy-based machine learning implementation
