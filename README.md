# Fraud Detection ML Project

Machine learning system for detecting fraudulent websites using multiple classification algorithms.

## Features

Analyzes website characteristics:
- URL length, special characters, subdomain count
- Domain age, popularity rank, SSL validity
- NLP suspicious score, image similarity score
- DNS query patterns, brand mismatch indicators

## Models

- **Random Forest** with hyperparameter tuning
- **Ensemble** (Random Forest + XGBoost + Logistic Regression)
- **Neural Network** with dropout and early stopping

## Key Techniques

- **SMOTE** for handling class imbalance
- **Threshold optimization** for precision-recall tuning
- **Grid search** for hyperparameter optimization
- **SHAP** for model interpretability

## Quick Start

```bash
pip install pandas numpy scikit-learn imbalanced-learn xgboost tensorflow shap
```

Run `main.ipynb` to:
1. Generate synthetic fraud dataset (1000 samples)
2. Train multiple models with class balancing
3. Evaluate performance and optimize thresholds
4. Analyze feature importance

## Results

Achieves competitive fraud detection performance with balanced precision/recall through advanced sampling techniques and threshold optimization.

## Dataset

Synthetic dataset with 70% genuine and 30% suspicious websites, balanced using SMOTE during training.
