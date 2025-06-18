# 🧠 Lesson: Underfitting and Overfitting

## 🧩 Overview

This lesson explains two of the most common problems in machine learning:
- **Underfitting**: When the model is too simple to learn patterns
- **Overfitting**: When the model learns the training data too well

We used **Decision Trees** and controlled their complexity using `max_leaf_nodes` to find the best balance.

---

## 🔑 Key Concepts Learned

### 1. **What is Underfitting?**
- Model is **too simple**
- Can't capture relationships between features and target
- Performs poorly **on both training and validation data**

### 2. **What is Overfitting?**
- Model is **too complex**
- Memorizes training data instead of learning general patterns
- Performs well on **training data**, but poorly on **validation/test data**

### 3. **How to Control Model Complexity**
Used the `max_leaf_nodes` parameter in `DecisionTreeRegressor`:
```python
model = DecisionTreeRegressor(max_leaf_nodes=100)