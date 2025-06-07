# Day 5 – Model Evaluation Metrics

Today's focus was on evaluating machine learning models using key metrics, including **Precision**, **Recall**, **F1-score**, and **ROC curve**. The goal was to assess the performance of classification models using these common evaluation methods.

## ✅ What I did
- Loaded and preprocessed the **Breast Cancer dataset** from `sklearn.datasets`.
- Scaled the data using `StandardScaler` for better model performance.
- Used various evaluation metrics such as:
  - **Precision**: Accuracy of positive predictions.
  - **Recall**: Ability to detect all positive instances.
  - **F1-score**: Balance between precision and recall.
  - **Confusion Matrix**: Compared predicted vs actual values.
  - **ROC Curve**: Visualized model performance at various thresholds.

## 📊 Why this matters
Using these metrics helps in:
- **Understanding the trade-off** between Precision and Recall, especially in imbalanced datasets.
- **Assessing model performance** through various perspectives, not just accuracy.
- **Visualizing performance** with metrics like ROC curves, which help in threshold-based decision making.

## 🧠 Insights
- The models showed different strengths depending on the evaluation metric.
- **Logistic Regression** and **Decision Trees** performed well in terms of precision and recall, but their accuracy fluctuated depending on the threshold.
- The **ROC curve** highlighted how the models' true positive rate and false positive rate vary at different decision thresholds.

## 🔧 Next Steps
- Explore more complex models (e.g., Random Forest, SVM).
- Fine-tune hyperparameters to improve the performance metrics.
- Experiment with handling class imbalance and evaluate the impact on metrics like Recall and F1-score.
