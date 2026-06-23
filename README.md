# 🌸 Iris Dataset Classification

**Subject:** Machine Learning  
**Algorithms:** Logistic Regression & K-Nearest Neighbors (KNN)

## Overview

This project classifies the classic Iris dataset using two supervised learning algorithms — Logistic Regression and K-Nearest Neighbors. The goal is to predict the species of an iris flower (Setosa, Versicolor, or Virginica) based on its sepal and petal measurements.

## Dataset

The [Iris dataset](https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html) contains 150 samples across 3 classes with 4 features each:

- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

## Algorithms

**Logistic Regression** — a linear classifier that estimates class probabilities using the logistic function.

**K-Nearest Neighbors (KNN)** — a non-parametric algorithm that classifies a sample based on the majority class among its K nearest neighbors.

## Requirements

```bash
pip install numpy pandas scikit-learn matplotlib seaborn jupyter
```

## How to Run

```bash
jupyter notebook
```

Then open the `.ipynb` file and run all cells.

## Results

Both models are evaluated using accuracy score, confusion matrix, and classification report.
