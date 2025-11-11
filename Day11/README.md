# 🌲 Day 11 — Random Forest (Ensemble Learning)

### 🎯 Objective
Learn how **Random Forest**, an ensemble of Decision Trees, improves accuracy and reduces overfitting through averaging predictions.

---

## 📘 Topics Covered
1. **What is an Ensemble Model?**
   - Combines multiple weak learners (like Decision Trees) into a strong model.
   - Uses *Bagging* (Bootstrap Aggregation) to train each tree on random subsets of data.

2. **Random Forest Concept**
   - Builds several trees independently.
   - Final prediction is based on majority vote (classification) or average (regression).

3. **Advantages**
   - Reduces overfitting.
   - Works well for both classification and regression.
   - Provides feature importance.

---

## ⚙️ Key Parameters
| Parameter | Description |
|------------|-------------|
| `n_estimators` | Number of trees |
| `max_depth` | Maximum depth of each tree |
| `criterion` | Split metric (gini/entropy) |
| `random_state` | Ensures reproducibility |

---

## 📊 Evaluation Metrics
- Accuracy  
- Confusion Matrix  
- Feature Importance Plot  

---

## 🧠 Why It’s Useful
- Handles missing data well  
- Great default model for most problems  
- Foundation for advanced ensemble methods (e.g., Gradient Boosting, XGBoost)

