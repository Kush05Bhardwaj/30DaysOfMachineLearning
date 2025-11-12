# 🧭 Day 12 — K-Nearest Neighbors (KNN Classification)

### 🎯 Objective
Understand how the **K-Nearest Neighbors (KNN)** algorithm classifies new data based on its similarity to existing points.

---

## 📘 Topics Covered
1. **Concept of KNN**
   - Non-parametric, instance-based learning algorithm.  
   - Classifies a data point based on the **majority vote** of its K nearest neighbors.
   - Distance metric: usually **Euclidean distance**.

   \[
   d(p, q) = \\sqrt{(x_1 - y_1)^2 + (x_2 - y_2)^2 + \dots}
   \]

2. **Steps in KNN**
   1. Choose value of K  
   2. Compute distance of new point from all existing points  
   3. Select K nearest neighbors  
   4. Predict majority class among neighbors  

3. **Advantages**
   - Simple, interpretable, no training phase.  
   - Works well for small, clean datasets.

4. **Disadvantages**
   - Slow for large datasets.  
   - Sensitive to noisy or unscaled data.

---

## ⚙️ Evaluation
- Accuracy  
- Confusion Matrix  
- Effect of K-value on model performance  

