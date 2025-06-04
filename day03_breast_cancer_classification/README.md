# Day 3 – Model Comparison on Breast Cancer Dataset

In this notebook, I compared three supervised learning models:

- **Logistic Regression**  
- **K-Nearest Neighbors (KNN)**  
- **Decision Tree Classifier**

The dataset used was **Breast Cancer Wisconsin**, which is commonly used for binary classification problems.

## 🔍 Steps Taken:
- Loaded and explored the dataset  
- Preprocessed the data (including feature scaling)  
- Trained and evaluated each model  
- Compared their accuracy and performance metrics (confusion matrix, classification report)

## 📊 Observations:
- **Logistic Regression** achieved the best performance due to the linearly separable nature of the data and feature scaling.
- **KNN** was slightly less accurate and sensitive to local noise.
- **Decision Tree** tended to overfit and didn't generalize as well.

## ✅ Key Insight:
To improve the reliability of model evaluation, we plan to use **k-fold cross-validation** in future steps instead of relying on a single train-test split.
