Principal-Component-Analysis

1. Oerview of the project

This project has described the principal component analysis. Due to the enoromus features (curse of dimensionality) present in the dataset, it is always important to select/extract the best features which is productive to help in generating output.
So, PCA is one of the good feature selection technique. PCA reduces the higher dimension to lower dimension without loosing the gravity of the features and combines all correlated variables together.
It combines the features and reduces the dimension of the features. It doesn't mean that it ignores the features.
Mostly, the higher dimensional features have chances of overfitting so, PCA is a a way to eliminate the overfitting issue.

2. Problem statement:

In machine learning, it is said that almost 70% time is consumed in data preprocessing and feature engineering. Having extensive number of features creates more time consumption. This projct has vovered the following questions:-
What are the terms and termonologies comes into PCA?
What is the best process to get PCA?
How will we plot PCA in 2D?

3. Terms and Terminologies

a. Dimensionality:
It is the number of features in the dataset.

b. Correlation:
It is the relationship between two variables/features. It gives the strong, weak and no relation between the variables.

c. Principal Components:
After the reduction of the features, only certain correlated features from the overall features are obtained, called principal components.

d. Covariance Matrix:
It is the relationship between the movement of two predictors.

e. Eigen Vectors and Eigen Values
The characteristic vector of a square matrix does not changes its direction under the associated linear transformation, called eigen vectors.
If V is a vector that is not zero, than it is an eigenvector of a square matrix A if Av is a scalar multiple of v. This condition should be written as the equation: AV= λv. where, λ is a scalar known as the eigenvalue or characteristic value associated with eigenvector v.

4. Objectives:

The purpose of this project is to examine Principal Component Analysis(PCA) in Machine Learning. It will descibe through algorithm available in python sklearn to find the minimum features from higher dimension to lower dimension to observe the impact of less features in model building.

5. Problem analysis

I had applied a simple method (a complete and simplified explanation) to achieve the objectives in this project
I had imported python sklearn for the data analysis.

The following steps is normally followed in Principal Component Analysis:
  Standardization
  Covariance matrix computation
  Compute the eigenvectors and eigenvalues of the covariance matrix
  Feature vectors
  Recast the data along the Principal Component axes
