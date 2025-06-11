# Day 7 – Pipeline, XGBoost, and Cross-Validation Performance Analysis

In this notebook, I developed a machine learning pipeline that combines data preprocessing with model training using XGBoost. The goal for today was to create a reproducible workflow and perform a thorough evaluation using cross-validation.

---

## Tasks Completed:
- **Data Preprocessing:**  
  Applied `StandardScaler` to normalize the features.

- **Modeling with Pipeline:**  
  Built a pipeline combining the scaler with an `XGBClassifier` for classification.

- **Model Evaluation:**  
  Evaluated the pipeline using 10-fold cross-validation via `cross_validate`.  
  Displayed:
  - Average fit time
  - Average score time
  - Average accuracy (test score)

- **Results Summary:**  
  The notebook prints out the mean fit time, score time, and test accuracy to provide a concise summary of the model’s performance.

---

## Key Insights:
- The pipeline approach ensures consistent preprocessing and model evaluation, making the workflow reproducible.
- Cross-validation (especially with `StratifiedKFold`) provides a robust estimate of model performance by accounting for variance across different splits.
- The results indicate that the XGBoost model performs reliably with acceptable training and prediction times.

---

## Next Steps:
- Further tune the hyperparameters using GridSearchCV or RandomizedSearchCV.
- Compare performance with other ensemble methods such as Random Forest.
- Visualize model performance metrics (e.g., ROC Curve, feature importances) in future experiments.
