# 🛠️ Day 20 — Feature Engineering

### 🎯 Objective
Transform raw data into meaningful features using:
- Scaling  
- Encoding  
- Polynomial Features  
- Feature Selection  
- Pipelines  

---

## 📘 Topics Covered

### 1. Scaling
Used to normalize numeric features.

- **StandardScaler**
\[
z = \frac{x - \mu}{\sigma}
\]

- **MinMaxScaler**
\[
x' = \frac{x - x_{min}}{x_{max} - x_{min}}
\]

### 2. Encoding
Convert categories into numbers:
- **Label Encoding**  
- **One Hot Encoding**

### 3. Polynomial Features
Adds interaction terms:
x, y → x, y, x², y², xy
Useful for non-linear models.

### 4. Feature Selection
Select only the top-k important features.

### 5. Pipeline
Chain transformations → model training in one go.


