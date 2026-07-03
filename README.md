# Machine Learning Algorithms

A collection of Machine Learning algorithms implemented using **Python**, **Scikit-learn**, and **TensorFlow/Keras**. This repository is organized into **Supervised** and **Unsupervised** Machine Learning algorithms with practical implementations on real-world datasets.

---

# Repository Structure

```text
Machine-Learning-Algorithms/
│
├── Supervised/
│   ├── linear_regression.ipynb
│   ├── logistic_regression.ipynb
│   ├── knn.ipynb
│   ├── decision_tree.ipynb
│   ├── random_forest.ipynb
│   ├── ann.ipynb
│   ├── svm.ipynb
│   └── naive_bayes.ipynb
│
├── Unsupervised/
│   ├── kmeans.ipynb
│   └── pca.ipynb
│
├── datasets/
│   ├── heart.csv
│   └── students.csv
│
└── README.md
```

---

# Algorithms Implemented

## Supervised Learning

- Linear Regression
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Artificial Neural Network (ANN)
- Support Vector Machine (SVM)
- Naive Bayes

## Unsupervised Learning

- K-Means Clustering
- Principal Component Analysis (PCA)

---

# Datasets Used

### Heart Disease Dataset

Used for:

- Logistic Regression
- KNN
- Decision Tree
- Random Forest
- ANN
- SVM
- Naive Bayes
- PCA + Logistic Regression

### Students Dataset

Used for:

- K-Means Clustering

---

# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Jupyter Notebook
- Git
- GitHub

---

# Machine Learning Workflow

Most supervised learning projects follow this workflow:

1. Import Libraries
2. Load Dataset
3. Select Features (X) and Target (y)
4. Train-Test Split
5. Feature Scaling (when required)
6. Create Model
7. Train Model
8. Make Predictions
9. Evaluate Performance

For PCA:

1. Import Libraries
2. Load Dataset
3. Train-Test Split
4. Feature Scaling
5. Apply PCA
6. Train Classification Model
7. Evaluate Performance

---

# Algorithms Overview

| Algorithm | Type | Main Idea |
|-----------|------|-----------|
| Linear Regression | Supervised | Predict continuous values using the best-fit line |
| Logistic Regression | Supervised | Binary classification using the Sigmoid function |
| KNN | Supervised | Predict using nearest neighbors |
| Decision Tree | Supervised | Learn decision rules by splitting data |
| Random Forest | Supervised | Combine multiple Decision Trees using voting |
| ANN | Supervised | Learn complex patterns using artificial neurons |
| SVM | Supervised | Find the optimal hyperplane with maximum margin |
| Naive Bayes | Supervised | Predict using Bayes' Theorem and probability |
| K-Means | Unsupervised | Group similar data into clusters |
| PCA | Unsupervised | Reduce dimensions while preserving maximum variance |

---

# Model Performance

| Algorithm | Accuracy |
|-----------|---------:|
| Logistic Regression | **75.12%** |
| KNN | **87.8%** |
| Decision Tree | **78.54%** |
| Random Forest | **100.00%*** |
| ANN | **78.05%** |
| SVM | **81.46%** |
| Naive Bayes | **75.12%** |
| PCA + Logistic Regression | **77.56%** |

> **Note:** PCA reduces the number of features before classification. It improves efficiency by reducing dimensionality, although some predictive information may be lost.

> **Note:** The Random Forest result of **100%** should be interpreted carefully. In practice, an unusually high score should always be checked to ensure there is no data leakage or evaluation issue.

---

# Evaluation Metrics

Models are evaluated using:

- Accuracy Score
- Confusion Matrix
- Explained Variance Ratio (PCA)
- Training Accuracy (ANN)
- Testing Accuracy (ANN)
- Loss Function (ANN)

---

# Learning Objectives

This repository documents my Machine Learning learning journey. The objective is to understand the intuition, implementation, and practical application of classical Machine Learning algorithms through coding, experimentation, and evaluation.

---

# Future Additions

- Cross Validation
- Hyperparameter Tuning
- XGBoost
- AdaBoost
- Gradient Boosting
- Principal Component Analysis (Advanced)
- Feature Engineering
- Model Deployment using Flask / Streamlit

---

# Author

**Vignesh Kotrica**