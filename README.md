# Unsupervised & Supervised Machine Learning

This repository contains the Jupyter Notebook and associated files for Practical Session 1, which focuses on both unsupervised and supervised machine learning techniques. The dataset used is the MIT-BIH Arrhythmia database, consisting of 10,000 electrocardiograms (ECGs) with 180 time samples each. The ECGs are labeled with one of five categories:

1. 'A': Atrial premature beat
2. 'L': Left bundle branch block beat
3. 'N': Normal beat
4. 'R': Right bundle branch block beat
5. 'V': Premature ventricular contraction

## Notebook Structure
The notebook is divided into two main parts:

### 1. Unsupervised Learning
- **Principal Component Analysis (PCA)**: Dimensionality reduction and visualization of the data.
- **Clustering (K-Means)**: Application of K-Means clustering to the data, with evaluation using homogeneity, completeness, and V-measure metrics.

### 2. Supervised Learning
- **Logistic Regression**: Implementation and evaluation of a logistic regression model.
- **Gaussian Naive Bayes Classifier**: Implementation and evaluation of a Naive Bayes model.
- **Support Vector Machine (SVM)**: Implementation and evaluation of SVM models with both RBF and linear kernels.

### Bonus
- **Random Forest Classifier**: Implementation and evaluation of a Random Forest model as a bonus exercise.

## Results
The notebook includes detailed explanations, code implementations, and visualizations for each step of the analysis. Key results include:
- **PCA**: Determination of the number of components needed to retain 95% of the variance.
- **K-Means Clustering**: Evaluation of clustering performance using homogeneity, completeness, and V-measure.
- **Supervised Models**: Accuracy scores and confusion matrices for logistic regression, Naive Bayes, and SVM models.
- **Random Forest**: Bonus implementation with high test accuracy.
