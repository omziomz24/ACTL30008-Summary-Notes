# ACTL30008: Actuarial Data Analytics I - Comprehensive Summary Notes

This repository contains my comprehensive summary notes for the subject **ACTL30008: Actuarial Data Analytics I**, completed at the University of Melbourne. These notes are designed to provide a structured and detailed breakdown of all key topics covered in the course, with a focus on both theoretical concepts and practical applications using the R programming language.

The notes were compiled to be a single, all-encompassing resource for revision and reference. They are formatted in LaTeX for clear presentation of mathematical and statistical notation.

## Subject Breakdown

The course, Actuarial Data Analytics I, provides an introduction to the fundamental tools and techniques of statistical learning and their application within the actuarial field. The curriculum is structured to build a strong foundation, starting from classical linear models and progressing to more modern, flexible methods.

Here's a rough breakdown of the key topics covered in the notes:

### 1. Introduction to Statistical Learning
* **Core Concepts:** Defines statistical learning, distinguishes between supervised and unsupervised learning, and introduces the crucial concepts of prediction vs. inference.
* **Model Accuracy:** Explores how to measure prediction error for both regression (Mean Squared Error) and classification (Misclassification Rate).
* **Bias-Variance Trade-off:** A foundational principle of the subject, explaining how model flexibility impacts bias, variance, and overall test error.

### 2. Linear Regression
* **Simple Linear Regression:** Covers the theory, assumptions, and practical application of linear regression with a single predictor.
* **Multiple Linear Regression:** Extends the model to multiple predictors, discussing coefficient interpretation, F-tests, t-tests, dummy variables, and interaction terms.
* **Model Diagnostics:** Explains how to identify potential problems like non-linearity, correlated errors, non-constant variance (heteroscedasticity), outliers, high-leverage points, and collinearity.

### 3. Resampling Methods
* **Purpose:** Explains why resampling is necessary to estimate test error and validate model performance.
* **Techniques:** Details the **Validation Set Approach**, **Leave-One-Out Cross-Validation (LOOCV)**, and **K-Fold Cross-Validation**, comparing their biases and variances.
* **Bootstrap:** Discusses how the bootstrap method is used to quantify the uncertainty of an estimator or a model's coefficients.

### 4. Linear Model Selection & Regularization
* **Objective:** Addresses the challenges of model selection when dealing with many predictors.
* **Subset Selection:** Describes **Best Subset Selection** and the computationally efficient **Forward** and **Backward Stepwise Selection** methods.
* **Shrinkage Methods (Regularization):** Covers **Ridge Regression** and **Lasso Regression**, explaining how they shrink coefficients to reduce variance and improve model performance, especially when $p > n$.

### 5. Non-linear Models
* **Beyond Linearity:** Introduces methods to capture non-linear relationships.
* **Techniques:** Explores **Polynomial Regression**, **Step Functions**, and various types of **Splines** (Regression and Smoothing Splines) to add flexibility to models.
* **Generalized Additive Models (GAMs):** An extension of linear models that allows for flexible, non-linear relationships for each predictor while maintaining additivity for interpretability.

### 6. Classification Methods
* **Logistic Regression:** A cornerstone of classification, this section explains how to model the probability of a binary outcome. It covers the logistic function, log-odds interpretation, and fitting via maximum likelihood.
* **Discriminant Analysis:** Explains **Linear Discriminant Analysis (LDA)** and **Quadratic Discriminant Analysis (QDA)**, highlighting their assumptions and trade-offs.
* **K-Nearest Neighbors (KNN):** A simple, non-parametric method for classification, discussing the role of the parameter K and the pros and cons of the approach.
* **Evaluation:** Covers **Confusion Matrices**, **ROC curves**, and various performance metrics like sensitivity and specificity.

### 7. Trees & Support Vector Machines
* **Decision Trees:** Introduces both **Regression** and **Classification Trees**, explaining the recursive binary splitting algorithm. It also covers the importance of **tree pruning** to avoid overfitting.
* **Support Vector Machines (SVMs):** A powerful classification method based on finding an optimal hyperplane. The notes detail the **Maximal Margin Classifier**, **Support Vector Classifiers (soft-margin)**, and the use of **Kernels** (linear, polynomial, radial) to handle non-linear boundaries.

### 8. Unsupervised Learning
* **Introduction:** Explores the goals and challenges of learning from data without a response variable.
* **Principal Component Analysis (PCA):** A dimensionality reduction technique used for data visualization or as a pre-processing step. Explains how to find principal components, interpret loadings, and determine the number of components to retain.
* **Clustering:** Covers methods to find subgroups within data, specifically **K-Means Clustering** (requiring a pre-specified number of clusters) and **Hierarchical Clustering** (generating a dendrogram to visualize nested clusters).

## Appendix: R Code & Formulas

The notes are heavily annotated with R code examples for each model, demonstrating how to fit models, interpret outputs, and generate diagnostic plots. An appendix provides a quick reference guide to essential R functions and a summary of the bias-variance trade-off for each model type.

This repository serves as a valuable resource for anyone studying or revising for ACTL30008, or for anyone seeking a concise yet comprehensive guide to foundational data analytics concepts.
