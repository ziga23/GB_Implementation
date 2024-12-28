[![LinkedIn Logo](https://img.icons8.com/ios-filled/50/0077b5/linkedin.png)](https://www.linkedin.com/in/михаил-зигангиров-78018326b/)

# Gradient Boosting Implementation
This repository contains a manual implementation of gradient boosting,
a powerful ensemble learning method that combines multiple simple models (base learners) to create a stronger predictive model. 
The project demonstrates the fundamentals of gradient boosting and compares the manual implementation with the sklearn library's implementation.

## Project Goals
1. Implement gradient boosting manually using decision trees as base learners.
2. Compare the manual implementation with sklearn's implementation by evaluating error metrics on a small dataset.
3. Explore the differences in performance and interpretability between the two implementations.

## What is Gradient Boosting?
Gradient boosting is an iterative learning technique that optimizes a model by combining several weak models (e.g., decision trees). Unlike traditional boosting, gradient boosting uses pseudo-residuals, which are gradients of the loss function with respect to predictions, to build new models that minimize error more effectively.

## Features
- Manual implementation of gradient boosting from scratch.
- Comparison with sklearn.ensemble.GradientBoostingRegressor.
- Use of error metrics such as RMSE and MAE for regression tasks.
- Visualization of error convergence and feature importance.

## Files in the Repository
- [gradient_boosting.ipynb](): Jupyter Notebook containing the code for manual gradient boosting implementation and comparisons.
- README.md: This file.

## References
- [Gradient Boosting (Wikipedia)](https://en.wikipedia.org/wiki/Gradient_boosting)
- [Sklearn Gradient Boosting Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingRegressor.html#sklearn.ensemble.GradientBoostingRegressor)
