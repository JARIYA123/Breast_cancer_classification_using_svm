# Breast_cancer_classification_using_svm
# 📌 Overview

This mini project demonstrates how Support Vector Machine (SVM) can be used to classify breast cancer tumors as malignant or benign.A linear SVM model is trained on the Breast Cancer dataset from scikit-learn, and the decision boundary is visualized using two features.
# 🎯 Objective

1. Build a machine learning classification model using SVM .
2. Understand how SVM separates two classes .
3. Visualize the decision boundary .
4. Gain hands-on experience for ML interviews and projects .
# 📊 Dataset Information

Source: Scikit-learn built-in dataset ,
Samples: 569 ,
Features: 30 numerical features ,
Target Classes:
0 → Malignant ,
1 → Benign .
✔Only the first two features are used for visualization purposes.
# 🛠️ Technologies Used

Python,
Scikit-learn,
Matplotlib,
NumPy.
# 🔄 Project Workflow

1. Load the breast cancer dataset.
2. Select features and target labels.
3. Split data into training and testing sets.
4. Train a Linear SVM model.
5. Evaluate the model.
6. Visualize the decision boundary.
# 📁 Project Structure

breast-cancer-svm/
│
├── svm_breast_cancer.py
├── README.md
# 🧪 Model Used

Algorithm: Support Vector Machine (SVM) ,
Kernel: Linear ,
Library: sklearn.svm.SVC .
## 🧾 Code Explanation (Main Steps)
# Load Dataset
from sklearn.datasets import load_breast_cancer
cancer = load_breast_cancer()
X = cancer.data[:, :2]
y = cancer.target

