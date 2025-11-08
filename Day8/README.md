# 🚢 Day 08 — Logistic Regression (Titanic Classification)

### 🎯 Objective
Learn Logistic Regression — a **supervised ML algorithm** used for **classification problems** (e.g., predicting survival, spam detection, disease diagnosis).

---

## 📘 Topics Covered
1. **What is Logistic Regression?**  
   - Used when the target variable is categorical (e.g., 0/1).  
   - Predicts probabilities using the **sigmoid function**:
     \[
     \sigma(z) = \\frac{1}{1 + e^{-z}}
     \]
   - Output: values between 0 and 1 (interpreted as probabilities)

2. **Dataset Used:**  
   Titanic Survival Dataset (simplified version).  
   Features: Age, Fare, Gender → Target: Survived (0 or 1)

3. **Implementation Steps:**
   - Data Cleaning (handle missing values, encode categorical variables)
   - Train Logistic Regression Model
   - Evaluate using Accuracy, Precision, Recall, F1-Score
   - Visualize Confusion Matrix

---

## 📊 Evaluation Metrics

| Metric | Meaning | Ideal Value |
|----------|----------|-------------|
| **Accuracy** | Overall correctness | High |
| **Precision** | True Positives / (TP + FP) | High |
| **Recall** | True Positives / (TP + FN) | High |
| **F1-Score** | Harmonic mean of precision & recall | High |

---
