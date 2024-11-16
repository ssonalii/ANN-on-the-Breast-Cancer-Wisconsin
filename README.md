# ANN-on-the-Breast-Cancer-Wisconsin
# Tumor Classification Using ANN

This project uses Artificial Neural Networks (ANN) with Bayesian
optimization to classify tumors as benign or malignant using the
Breast Cancer Wisconsin Dataset.

## Objective
- Develop a high-performance ANN for tumor classification.
- Optimize hyperparameters (dropout, learning rate, hidden units)
using Bayesian methods.
- Evaluate using sensitivity, specificity, and MCC.

## Dataset
-   Source  : [Kaggle - Breast Cancer Wisconsin
Dataset](https://www.kaggle.com/code/nadaemad2002/breastcancer-wisconsin)
-   Features  : 30 attributes including size, texture, and shape.
-   Target  : Binary classification - 0 (Benign), 1 (Malignant).

## Methodology
-   Model  :
  - Input: 30 features.
  - Hidden Layers: 3 layers with ReLU, dropout.
  - Output: Sigmoid for binary classification.
-   Optimization  : Bayesian optimization for hyperparameter tuning.
-   Metrics  : Sensitivity, Specificity, MCC.

## Results
- High sensitivity and specificity for reliable classification.
- Optimized hyperparameters enhanced accuracy and generalization.

## Technologies
- Python, TensorFlow, scikit-learn, scikit-optimize.
- Libraries: pandas, numpy, matplotlib, seaborn.

## Future Work
- Integrate advanced architectures like CNNs.
- Use multi-modal data for enhanced insights.
- Add model interpretability tools (SHAP, LIME).

## References
- Dataset: [Breast Cancer Wisconsin
Dataset](https://www.kaggle.com/code/nadaemad2002/breastcancer-wisconsin)
