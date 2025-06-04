# 📌 Lesson: How Models Work

## 🧠 Overview
This notebook from Kaggle explains the basics of how machine learning models work, focusing on:
- Features vs Target variables
- Training a simple model (Decision Tree)
- Making predictions
- Measuring model accuracy

## 🛠️ Key Concepts Learned

### ✅ What is a Model?
A model learns patterns from data (features) to predict something (target).

### 🎯 Features vs Target
- **Features**: Input variables (e.g., number of bedrooms, square feet)
- **Target**: Output variable (e.g., house price)

### 🌳 Decision Tree
- A simple model that splits data into branches to make decisions/predictions.
- Easy to understand and visualize.

### 🧪 Model Evaluation
Used `mean_absolute_error()` to evaluate how accurate predictions are.

## 📚 Code Highlights

```python
from sklearn.tree import DecisionTreeRegressor
model = DecisionTreeRegressor()
model.fit(X, y)
predictions = model.predict(X)