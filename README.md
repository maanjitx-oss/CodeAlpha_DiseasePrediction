# Disease Prediction from Medical Data

CodeAlpha Machine Learning Internship - Task 4

## Objective
Predict whether a tumor is malignant or benign using patient data.

## Dataset
Breast Cancer Wisconsin dataset (UCI ML Repository, via scikit-learn).

## Approach
- Data exploration and cleaning
- Feature scaling (StandardScaler)
- Train/test split (80/20)
- Models: Logistic Regression, Random Forest, SVM
- Evaluation: Precision, Recall, F1-Score, ROC-AUC

## Results
| Model | Accuracy | ROC-AUC |
|---|---|---|
| Logistic Regression | 0.97 | 0.9974 |
| Random Forest | 0.96 | 0.9953 |
| SVM | 0.98 | 0.9974 |

Best model: SVM (Accuracy 0.98, ROC-AUC 0.997)

## Tools
Python, Pandas, Scikit-learn, Google Colab
