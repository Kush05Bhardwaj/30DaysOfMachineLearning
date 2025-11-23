# ⚖️ Day 23 — Imbalanced Data (SMOTE + Class Weights)

### 🎯 Objective
Learn techniques to handle **imbalanced datasets**, where one class is significantly smaller than the other.  
You will implement:
- Logistic Regression on imbalanced data
- **SMOTE** (Synthetic Minority Oversampling Technique)
- **Class Weights** adjustment
- Visual comparison before/after oversampling

---

## 📘 Topics Covered

### 1. What is Imbalanced Data?
A dataset where the distribution of target classes is uneven.  
Example:
- Class 0 → 90%
- Class 1 → 10%

This causes the model to predict mostly the majority class.

---

## ❌ Problem Without Fixing Imbalance
- High accuracy but BAD recall for minority class  
- Confusion matrix showing incorrect behavior  
- Model becomes biased toward majority class  

---

## ✔️ Method 1 — SMOTE (Oversampling)
SMOTE generates synthetic samples for the minority class:
Advantages:
- Works well for numeric data  
- Prevents overfitting more than random oversampling  

---

## ✔️ Method 2 — Class Weights
Use model parameter:
This makes the model pay **more attention** to minority samples during training.



