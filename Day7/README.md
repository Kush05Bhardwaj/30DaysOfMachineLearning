# 🏠 Day 07 — Multiple Linear Regression (House Price Prediction)

### 🎯 Objective
Apply Multiple Linear Regression to predict **house prices** using multiple features such as area, bedrooms, and age.

---

## 📘 Topics Covered
1. **What is Multiple Linear Regression?**  
   - Extends simple regression to multiple input variables  
   \[
   y = b_0 + b_1x_1 + b_2x_2 + \dots + b_nx_n
   \]
2. **Model Training**  
   - Load dataset  
   - Train `LinearRegression()` model  
   - Evaluate using R² and RMSE  
3. **Feature Importance**  
   - Interpret model coefficients  
4. **Visualization**  
   - 2D/3D scatter plots and predicted vs actual values  

---

## 🧠 Intuition
- Each feature adds a new dimension to the regression line → forming a **plane (or hyperplane)**.  
- The model learns weights (`b₁, b₂, ...`) for each feature to best predict the target (price).

---

## 🧮 Evaluation Metrics
| Metric | Meaning | Ideal Value |
|----------|----------|-------------|
| **R² (R-squared)** | Proportion of variance explained by model | Closer to 1 |
| **RMSE (Root Mean Squared Error)** | Average prediction error | Lower is better |

---