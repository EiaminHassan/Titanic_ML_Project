# 🚢 Titanic Survival Prediction - Machine Learning Project

Predicting the survival of passengers on the Titanic using machine learning techniques like Logistic Regression, Decision Trees, and Random Forests.

## 📌 Project Overview

This project uses the famous Titanic dataset from [Kaggle](https://www.kaggle.com/c/titanic) to build a classification model that predicts whether a passenger survived or not based on features like age, gender, class, etc.

---

## 🔍 Project Pipeline

1. **Data Preprocessing** (`data_cleaning.ipynb`)
   - Handling missing values
   - Feature engineering
   - Encoding categorical features

2. **Exploratory Data Analysis (EDA)** (`eda.ipynb`)
   - Understanding feature distributions
   - Correlation analysis
   - Visualizations with seaborn/matplotlib

3. **Model Building & Evaluation** (`model_training.ipynb`)
   - Models used:
     - Logistic Regression ✅
     - Random Forest Classifier 🌲
     - Decision Tree
   - Evaluation metrics:
     - Accuracy
     - Confusion Matrix
     - Cross-validation

4. **Model Inference** (`model_prediction.ipynb`)
   - Load saved model and scaler
   - Make predictions on test data
   - Save outputs to CSV

---

## 🎯 Final Model Performance

| Model                | Accuracy | Cross-Validation |
|---------------------|----------|------------------|
| Logistic Regression | 0.82     | 0.81             |
| Random Forest       | 0.84     | 0.80             |
