# Telecom-Churn-predictor-model
Customer Churn Prediction using ANN (PyTorch) with SMOTE for handling class imbalance. Achieved ~81% accuracy and improved recall for churn class.
# Customer Churn Prediction using ANN (PyTorch)

## Project Overview
This project builds an Artificial Neural Network (ANN) using PyTorch to predict customer churn. The model is trained on the Telco Customer Churn dataset and focuses on improving performance on the minority class (churn customers).

---

## Objectives
- Predict whether a customer will churn or not
- Handle class imbalance effectively
- Improve recall for churn customers

---

## Techniques Used
- Data Preprocessing (Encoding, Scaling)
- One-Hot Encoding (`pd.get_dummies`)
- Train-Test Split
- StandardScaler
- Artificial Neural Network (ANN) using PyTorch
- SMOTE (Synthetic Minority Over-sampling Technique)
- Model Evaluation (Accuracy, Precision, Recall, F1-score)

---

## Model Architecture
- Input Layer: Number of features
- Hidden Layers: 64 → 32 → 16 → 8
- Activation: ReLU
- Output Layer: 1 neuron (Sigmoid)

---

## Results

| Metric        | Score |
|--------------|------|
| Accuracy     | ~0.81 |
| Precision    | 0.65 (Churn) |
| Recall       | 0.65 (Churn) |
| F1-score     | 0.65 |

---

## Key Improvements
- Applied SMOTE to balance dataset
- Improved churn detection (recall increased from ~0.55 to ~0.65)
- Built deeper ANN for better learning

---

## Key Insight
In churn prediction, recall is more important than accuracy because missing a churn customer can lead to business loss.

---

## Tech Stack
- Python
- PyTorch
- Scikit-learn
- Pandas
- NumPy

---

## Dataset
Telco Customer Churn Dataset

---

## Future Improvements
- Hyperparameter tuning
- Dropout & Regularization
- ROC-AUC optimization

---

## Conclusion
This project demonstrates how ANN combined with SMOTE can effectively handle imbalanced datasets and improve prediction performance for critical business problems like customer churn.
