# 🚨 Day 18 — Anomaly Detection (Outlier Detection)

### 🎯 Objective
Learn how to detect unusual data points using:
1. **Z-Score Method** (classical statistics)
2. **Isolation Forest** (machine learning)

---

## 📘 Topics Covered

### 1. What is Anomaly Detection?
Process of identifying data points that do NOT fit the normal pattern.

Used in:
- Fraud detection  
- Network intrusion  
- Manufacturing defects  
- Medical abnormalities  

---

## 🧪 Methods Covered

### ⭐ 1. Z-Score Method
Formula:
\[
Z = \frac{(x - \mu)}{\sigma}
\]
If |Z| > 3 → Outlier

### ⭐ 2. Isolation Forest
- Popular ML method  
- Isolates anomalies by constructing random trees  
- Efficient for high-dimensional data
