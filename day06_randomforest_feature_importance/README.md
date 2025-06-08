# 📅 Day 6 – Random Forest Classification and Hyperparameter Tuning

In this notebook, I explored **Random Forest**, a powerful ensemble learning algorithm, and evaluated its performance on the breast cancer dataset.

---

## 🔧 Tasks completed:
- Trained a **Random Forest Classifier**.
- Tuned hyperparameters using **GridSearchCV**:
  - Parameters included: `n_estimators`, `max_depth`, and `min_samples_split`.
- Evaluated model using:
  - Accuracy
  - Classification report
  - ROC Curve and AUC Score
- Plotted **feature importances** to interpret the model.

---

## 📊 Observations:
- After tuning, the model achieved strong performance metrics.
- ROC curve showed a high AUC score, indicating good separability between classes.
- Features like `mean radius`, `mean concavity`, and `mean texture` had the highest importances.

---

## 🔍 Why some features were more important:
Features with high importance contributed the most to reducing impurity in the forest. For example, `mean radius` is highly correlated with malignancy, so it appeared more often in decision paths and helped improve model performance.

---

## 💡 Notes:
Although GridSearchCV was used here, **RandomizedSearchCV** can be an efficient alternative when:
- The hyperparameter space is large.
- Training time is a concern.
- A good-enough solution is preferred over an exhaustive search.
