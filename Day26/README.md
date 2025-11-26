# 🚢 Day 26 — Titanic Survival Prediction (Classification Project)

### 🎯 Objective
Build a complete **classification ML pipeline** to predict if a passenger survived, using:
- Exploratory Data Analysis (EDA)
- Preprocessing (Missing values, encoding, scaling)
- Model training
- Evaluation (Accuracy, F1, Confusion Matrix)
- Saving model for deployment readiness

---

## 📘 Dataset
- Famous *Titanic dataset*
- Target: `Survived` (0 = No, 1 = Yes)
- Key features used: `Pclass`, `Sex`, `Age`, `SibSp`, `Fare`, etc.

---

## 🧠 Steps Implemented in Notebook

### 1. **EDA**
- Visualized distributions of age, fare, class, gender
- Analyzed survival patterns using plots

### 2. **Data Cleaning**
- Filled missing `Age` with median
- Filled missing `Fare` with mean
- Dropped/encoded categorical features

### 3. **Feature Engineering**
- Label encoded `Sex`
- Scaled numeric features using `StandardScaler`

### 4. **Model Trained**
- Logistic Regression
- Random Forest Classifier

### 5. **Metrics Used**
| Metric | Purpose |
|--------|---------|
| Accuracy | Overall correctness |
| F1 Score | Balance between precision & recall |
| Confusion Matrix | Error pattern analysis |

---

## ✅ Key Learnings
- How to perform dataset analysis
- Handling missing values
- Encoding categorical data
- Training multiple models for comparison
- Evaluating classification models effectively
- Preparing a model for real-world deployment
