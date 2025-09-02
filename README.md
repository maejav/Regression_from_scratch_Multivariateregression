# 📊 Machine Learning Projects: Student Score & California Housing Price Prediction

This repository contains two end-to-end machine learning projects:

1. 🎓 **Student Score Prediction** — Predicting exam scores based on hours studied  
2. 🏡 **California Housing Price Prediction** — Estimating house prices using engineered features and regression models

---

## 🎓 Student Score Prediction

### 🔍 Overview
This project demonstrates how to predict student scores based on hours studied using:
- A custom implementation of linear regression with gradient descent
- A built-in model using `scikit-learn`

### 📂 Dataset
- Source: [Student Scores CSV](https://raw.githubusercontent.com/AdiPersonalWorks/Random/master/student_scores%20-%20student_scores.csv)
- Features:
  - `Hours`: Number of hours studied
  - `Scores`: Score obtained

### 📊 Visualization
```python
plt.scatter(df["Hours"], df["Scores"], color="skyblue")
plt.xlabel("Study Hours")
plt.ylabel("Scores")
plt.title("Student Scores Based on Study")
