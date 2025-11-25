# 🏡 Day 25 — House Price Prediction (Full ML Pipeline)

### 🎯 Objective
Build a **complete end-to-end machine learning project** for predicting house prices using:
- Preprocessing
- Feature scaling
- Regression model
- Evaluation (RMSE, R²)
- Saving & loading model for deployment

---

## 📘 Steps Performed

### 1. **Dataset Creation**
We generated a synthetic housing dataset with features:

- `Size_sqft`  
- `Rooms`  
- `Age_Years`  
- `Price` (Target)

Formula included randomness to simulate real estate noise.

---

### 2. **Train-Test Split**
Data split into:

- 80% training  
- 20% testing  

Ensures fair evaluation.

---

### 3. **Feature Scaling**
Applied `StandardScaler` to normalize:

- Size  
- Rooms  
- Age  

Scaling is crucial for regression to improve convergence.

---

### 4. **Model Training**
Trained **Linear Regression** on scaled features.

This makes the model learn relationships:  
- Bigger houses → higher price  
- More rooms → higher price  
- Older houses → slightly lower price  

---

### 5. **Evaluation**
You computed:

- **RMSE** (Root Mean Squared Error)  
- **R² Score** (Goodness of fit)

Example expected results:

---

### 6. **Visualization**
Plotted **Actual vs Predicted Prices**  
Shows how well model fits real trends.