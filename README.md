# Binary Classification of Alzheimer's and Progressive Supranuclear Palsy (PSP) using Scikit-learn

## Overview
This project implements a binary classification task using gene expression data sourced from RNA sequencing to differentiate between Alzheimer's disease (AD) and Progressive Supranuclear Palsy (PSP). The dataset consists of gene expression levels from brain tissue samples, with labels indicating the diagnosed disorder.

We explore multiple machine learning techniques, including Support Vector Machines (SVM), Logistic Regression, and Random Forest classifiers. Various feature selection and dimensionality reduction techniques are applied to handle the high-dimensionality of the gene expression data.

## Contents
The project includes the following key sections:
- **Data Importing and Preprocessing**: Preprocesses the gene expression data and labels, including encoding and cleaning the data.
- **Feature Selection and Dimensionality Reduction**: Applies random feature selection, variance-based selection, and Principal Component Analysis (PCA).
- **Support Vector Machine Classifier**: Utilizes GridSearchCV to tune hyperparameters and evaluate the SVM classifier.
- **Logistic Regression**: Implements Logistic Regression with L1 (lasso) and L2 (ridge) regularization and explores the effect of varying regularization strengths.
- **Random Forest Classifier**: Builds and evaluates Random Forest models with varying tree counts and feature selection approaches.
  
## Dataset
The dataset used in this project is a gene expression matrix paired with diagnosis labels for Alzheimer's (AD) and Progressive Supranuclear Palsy (PSP). The original study can be found at:  
[Nature: Gene expression study](https://www.nature.com/articles/sdata201689)
