# 🔁 Day 19 — Model Validation (Cross-Validation)

### 🎯 Objective
Learn how to evaluate a model's stability using **Cross-Validation** techniques:
- K-Fold Cross Validation  
- Stratified K-Fold Cross Validation  
- Comparing CV performance  

---

## 📘 Topics Covered

### 1. Why Cross-Validation?
Train-Test Split is not always reliable — depending on the split, accuracy may vary.  
Cross-validation ensures **model stability** by testing the model on multiple folds.

---

## 🔁 1. K-Fold Cross Validation  
- Splits data into **K equal parts**  
- Trains on K-1 folds, tests on the remaining  
- Repeats K times  

### Pros  
- Good for general evaluation  

### Cons  
- Not ideal for imbalanced datasets  

---

## 🔁 2. Stratified K-Fold  
- Maintains class distribution across folds  
- Best for classification tasks  
- More stable than regular K-Fold  

