# Day 8 - Logistic Regression with Pipeline and Hyperparameter Tuning

## Summary
In this notebook, I used the Breast Cancer dataset from `sklearn.datasets` to build a logistic regression classifier. I implemented a machine learning pipeline to handle data scaling and modeling in a clean and efficient way.

I then used `GridSearchCV` to tune the hyperparameter `C` of the logistic regression model, which controls the regularization strength. The best model was selected based on cross-validation performance.

## Steps:
- Loaded the breast cancer dataset.
- Built a pipeline with `StandardScaler` and `LogisticRegression`.
- Used `GridSearchCV` to tune the `C` parameter.
- Evaluated the best model and interpreted the results.

## Notes:
- A pipeline ensures that data transformation is done consistently during training and evaluation.
- The `C` parameter helps prevent overfitting by controlling the regularization applied to the model.

## Next Steps:
Try tuning more hyperparameters or comparing performance with tree-based models like Random Forest or Gradient Boosting.
