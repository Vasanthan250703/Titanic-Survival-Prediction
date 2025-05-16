# Titanic Survival Prediction

Predicting survival of passengers on the Titanic using machine learning classification models.

---

## Project Overview

This project analyzes the famous Titanic dataset to build models that predict whether a passenger survived the disaster. The dataset was preprocessed with appropriate handling of numerical and categorical features. Various classification algorithms were trained and evaluated to identify the best-performing model.

---

## Data Preprocessing

- Dropped features with many missing values or irrelevant information (e.g., `deck`, `embarked`, `embark_town`, `alive`).
- Handled missing data and encoded categorical variables using pipelines.
- Split data into training and testing sets.
- Applied Stratified K-Fold cross-validation for robust evaluation.

---

## Models Trained & Evaluated

| Model                         | Accuracy  |
|-------------------------------|----------:|
| Support Vector Classifier (SVC) | 83.24%   |
| Logistic Regression            | 82.68%   |
| Random Forest                 | 81.56%   |
| Gradient Boosting             | 81.56%   |
| K-Nearest Neighbors (KNN)      | 81.56%   |
| XGBoost                      | 81.01%   |

---

## Conclusion

- **Support Vector Classifier (SVC)** achieved the highest accuracy, demonstrating strong performance on this dataset.
- Logistic Regression also performed very well, indicating that the relationship between features and survival is somewhat linear.
- Ensemble methods like Random Forest and Gradient Boosting provided solid, consistent results.
- The similarity in accuracy among several models suggests that multiple approaches can effectively predict Titanic survival.
- Further improvements could include feature engineering, hyperparameter tuning, or more advanced models.

---

*This project was built as a comprehensive introduction to classification modeling using the Titanic dataset, covering data preprocessing, pipeline creation, model comparison, and evaluation techniques.*
