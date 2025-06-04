# 📊 Lesson: Basic Data Exploration

## 🧠 Summary

This lesson introduced the basics of data exploration using **pandas**, which is the primary tool in Python for working with structured data like tables.

### ✅ What I Learned:
- **Pandas** helps load, inspect, and manipulate datasets.
- Data is usually stored in a **DataFrame**, which is like a table with rows and columns.
- You can easily:
  - Check column names
  - View data
  - Find missing values
  - Understand data types and distributions

This step is essential before building any machine learning model because it helps us understand what data we are working with.

---

## 🔍 Key Concepts

### 📁 Loading Data
Used `pandas.read_csv()` to load the Melbourne housing dataset into a DataFrame:
```python
import pandas as pd
melbourne_data = pd.read_csv("melb_data.csv")