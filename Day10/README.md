# 🌳 Day 10 — Decision Trees (Classification + Visualization)

### 🎯 Objective
Understand how **Decision Trees** work for classification tasks and learn to train, visualize, and interpret them using scikit-learn.

---

## 📘 Topics Covered
1. **What is a Decision Tree?**
   - A supervised learning algorithm that splits data into smaller subsets based on conditions.
   - Works for both **classification** and **regression**.

2. **Key Concepts**
   - **Entropy:** Measures impurity or randomness in data  
     \[
     Entropy = -\\sum p_i \\log_2(p_i)
     \]
   - **Gini Index:** Another impurity measure used by default in scikit-learn  
     \[
     Gini = 1 - \\sum p_i^2
     \]
   - **Information Gain:** Reduction in impurity after a split

3. **Visualization**
   - Tree structure helps interpret model decisions
   - Easy to visualize feature importance

---

## 📊 Evaluation Metrics
- Accuracy  
- Confusion Matrix  
- Feature Importance Plot  

---

## 🧠 Why It’s Useful
Decision Trees are intuitive and form the base for **Random Forests** and **Gradient Boosting** — powerful ensemble methods coming next.
