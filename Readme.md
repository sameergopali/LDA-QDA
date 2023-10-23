# LDA and QDA Classifier Implementation

## Description

The notebook aims to implement Linear Discriminant Analysis (LDA) and Quadratic Discriminant Analysis (QDA) classifiers from scratch. LDA and QDA are powerful techniques used in machine learning and statistics for classification tasks, particularly when dealing with multivariate data.

## Linear Discriminant Analysis (LDA)

Linear Discriminant Analysis (LDA) is a dimensionality reduction technique and a classification algorithm. LDA seeks to find the linear combinations of features that best separate two or more classes in a dataset. It works by maximizing the between-class variance while minimizing the within-class variance. The key steps involved in LDA include:

- Calculation of class means and scatter matrices.
- Implementation of a decision boundary based on class means and variance, which effectively separates different classes in the dataset.

LDA is particularly useful when there are more than two classes and the classes exhibit some degree of separability.

## Quadratic Discriminant Analysis (QDA)

Quadratic Discriminant Analysis (QDA) is a classification algorithm closely related to LDA. While LDA assumes that the classes share a common covariance matrix, QDA allows each class to have its own covariance matrix. This makes QDA more flexible and capable of modeling complex decision boundaries. The key steps in QDA include:

- Calculation of class-specific means and covariance matrices.
- Evaluation of class probabilities using Bayes' theorem.
- Classification based on the estimated probabilities.

QDA is particularly valuable when dealing with data that does not conform to the assumptions of LDA, such as classes with different variances or non-linear decision boundaries.