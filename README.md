# 🧠 Machine Learning Projects

This repository contains a collection of coursework-based machine learning projects, 
covering fundamental algorithms and techniques in supervised and unsupervised learning.

---

## 🎯 Key Concepts Covered

- Linear Models & Logistic Regression  
- Classification Techniques  
- Decision Trees  
- Model Evaluation & Cross-Validation  
- Ensemble Methods (AdaBoost, Random Subspace)  
- Clustering (K-Means)  
- Dimensionality Reduction (PCA)  

---

## 🔹 1. Supervised Learning (Course Assignments)

This section includes three assignments developed during a university course on Machine Learning, focusing on core supervised learning concepts:

### 📌 Assignment 1 – Linear Models & Classification
- Logistic Regression (custom implementation)
- Multiclass classification (One-vs-One, One-vs-Rest)
- Data preprocessing (standardization)
- Feature importance analysis

### 📌 Assignment 2 – Decision Trees & Model Evaluation
- Decision Tree Regression
- Train/Validation/Test splits
- Cross-validation techniques:
  - K-Fold
  - Leave-One-Out
  - Nested Cross-Validation
- Hyperparameter tuning
- Model evaluation using multiple metrics

### 📌 Assignment 3 – Ensemble Methods
- Random Subspace method (custom implementation)
- AdaBoost (implemented from scratch)
- Use of sample weights in training
- Comparison with `scikit-learn` implementations

---

## 🔹 2. Unsupervised Learning (Additional Labs)

This section contains additional hands-on work focused on unsupervised learning techniques.

### 📌 K-Means Clustering
- Full implementation of the K-Means algorithm
- Cluster assignment & centroid updates
- Random initialization strategies
- Visualization of clustering process
- Application to **image compression**
- Selection of optimal number of clusters using MSE

### 📌 Principal Component Analysis (PCA)
- Feature normalization
- PCA implementation using Singular Value Decomposition (SVD)
- Explained variance analysis
- Dimensionality reduction & data projection
- Data reconstruction from reduced space
- Application to **face image compression**
- Visualization of principal components

---

## 📁 Repository Structure
```
machine-learning-course-projects/
│
├── assignments/                     # University coursework (supervised ML)
│   ├── assignment1/
│   │   └── assignment1_24_25.ipynb
│   │
│   ├── assignment2/
│   │   └── assignment2_24_25.ipynb
│   │
│   └── assignment3/
│       └── assignment3_24_25.ipynb
│
├── extras/                          # Additional practice / labs (unsupervised ML)
│   └── unsupervised-learning/
│       ├── lab_PCA/
│       │   ├── PCA.ipynb
│       │   ├── ex7data1.mat
│       │   ├── ex7faces.mat
│       │   └── images/
│       │
│       └── lab_Kmeans/
│           ├── K-means_Clustering.ipynb
│           ├── ex7data2.mat
│           ├── bird_small.mat
│           └── images/
│
├── .gitignore
└── README.md
```
---

## 🛠️ Technologies Used

- Python
- NumPy
- scikit-learn
- matplotlib
- scipy

---

## 📌 Notes

- The **supervised learning assignments** were developed as part of university coursework.  
- The **unsupervised learning labs** were completed independently to further explore practical applications of machine learning.
- All notebooks include detailed explanations (in Greek/English) and step-by-step implementations.