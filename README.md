# Python-Explanation-of-Standardisation-Standardization-
Standardization is a feature-scaling technique that transforms data to have a mean of 0 and a standard deviation of 1. This ensures that the features in a dataset are on a similar scale, improving the performance and convergence of machine learning models, especially those sensitive to the scale of input data.

Why Standardization is Important
Improves Model Performance:

Algorithms like Support Vector Machines (SVM), K-Nearest Neighbors (KNN), and Principal Component Analysis (PCA) are sensitive to the scale of data.
Standardization ensures no feature dominates due to its larger magnitude.
Speeds Up Convergence:

Gradient-based optimization algorithms (e.g., in logistic regression, neural networks) converge faster when features are standardized.
Handles Units in Data:

Standardization removes the effect of different units (e.g., kilometers vs. kilograms), making all features comparable.
Formula for Standardization
For each feature  standardized=(𝑋𝑖−𝜇)/𝜎

When to Use Standardization
Distance-Based Models: KNN, SVM, K-Means, PCA, etc., where distance metrics are used.
Gradient-Based Models: Logistic regression, neural networks, etc., to ensure features contribute equally to the optimization process.
Features with Different Scales: When features have vastly different ranges.
