# 📊 Day 09 — Model Metrics & Evaluation (Deep Dive)

### 🎯 Objective
Evaluate ML models beyond accuracy — using **precision, recall, F1-score, ROC, and AUC** to understand performance in real-world conditions.

---

## 📘 Topics Covered
1. **Confusion Matrix**
   - Shows model’s classification summary  
   - Metrics derived from it:
     - **Accuracy** = (TP + TN) / (TP + TN + FP + FN)  
     - **Precision** = TP / (TP + FP)  
     - **Recall (Sensitivity)** = TP / (TP + FN)  
     - **F1-Score** = 2 × (Precision × Recall) / (Precision + Recall)

2. **ROC & AUC**
   - ROC = Receiver Operating Characteristic  
   - AUC = Area Under Curve (measures model’s ability to separate classes)

3. **Precision-Recall Tradeoff**
   - Adjusting classification threshold changes precision and recall balance  

---

## 🧠 Why This Matters
Different models may have the same accuracy but vary greatly in recall or precision —  
especially critical for applications like:
- Medical diagnosis (high recall)
- Fraud detection (high precision)

---