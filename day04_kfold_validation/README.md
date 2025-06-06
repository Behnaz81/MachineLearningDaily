# Day 4 – K-Fold Cross-Validation and Model Comparison

Today’s focus was on evaluating models more reliably using **K-Fold Cross-Validation**. Instead of depending on a single train-test split, we used stratified k-fold to ensure balanced class distribution across folds.

## ✅ What I did
- Used `cross_val_score` from `sklearn.model_selection` to evaluate:
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Decision Tree
- Applied `StratifiedKFold` to preserve class proportions in each fold.
- Visualized the average accuracy of models using bar plots.
- Observed which models perform more consistently across folds.

## 📊 Why this matters
Using K-Fold Cross-Validation:
- Reduces the effect of random splits
- Gives a more generalizable estimate of model performance
- Helps detect overfitting (e.g., if accuracy varies widely across folds)

## 🧠 Insights
- Logistic Regression performed best overall, likely due to the linear nature of the dataset.
- KNN and Decision Tree were more sensitive to data characteristics and showed higher variance.
- Validating with multiple folds is more reliable than a single train-test evaluation.

## 🔧 Next Steps
- Try other metrics like precision and recall.
- Explore more robust techniques like GridSearchCV for hyperparameter tuning.
- Evaluate models on imbalanced datasets.

