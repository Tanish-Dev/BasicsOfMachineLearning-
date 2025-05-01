# Basics of Machine Learning

## Overview

This repository contains experiments and implementations of fundamental machine learning algorithms using Python. The project demonstrates various classification, clustering, and dimensionality reduction techniques applied to the classic Iris dataset.

## Dataset

The project uses the Iris dataset from the UCI Machine Learning Repository, which includes:

- 150 samples across 3 iris flower species
- 4 features: sepal length, sepal width, petal length, and petal width
- 3 classes: Setosa, Versicolor, and Virginica

## Techniques Implemented

### Classification Algorithms

- **Logistic Regression**: A linear model for binary classification extended for multi-class classification
- **Naive Bayes**: Probabilistic classifier based on applying Bayes' theorem
- **Decision Trees**: Non-parametric supervised learning method for classification
- **Random Forest**: Ensemble learning method that operates by constructing multiple decision trees
- **K-Nearest Neighbors (KNN)**: Instance-based classification method

### Clustering

- **K-Means**: Unsupervised learning algorithm that groups similar data points into clusters

### Dimension Reduction

- **Principal Component Analysis (PCA)**: Technique to reduce the dimensionality of the dataset

### Ensemble Methods

- **Random Forest Ensemble**: Using multiple random forests with 100 estimators
- **Gradient Boosting**: Sequential ensemble method that builds models to correct errors from previous ones

## Performance Evaluation

The project includes evaluation metrics for all implemented algorithms:

- Accuracy scores
- Classification reports (precision, recall, F1-score)
- Silhouette scores for clustering performance

## Data Preprocessing

- Standard scaling of features
- Train-test splitting
- Categorical data encoding
- Visualization using correlation heatmaps

## Requirements

- Python 3.x
- NumPy
- pandas
- scikit-learn
- Matplotlib
- Seaborn

## Getting Started

1. Clone this repository
2. Make sure you have all dependencies installed
3. Run the Jupyter notebook `BML_Exp.ipynb`

## Project Structure

```
BasicsOfMachineLearning-/
├── BML_Exp.ipynb      # Main Jupyter notebook with all implementations
└── README.md          # Project documentation
```

## Future Work

- Implementation of neural network models
- Feature engineering techniques
- Hyperparameter tuning
- Cross-validation methods

## License

This project is open source and available for educational purposes.

## Author

Tanish
