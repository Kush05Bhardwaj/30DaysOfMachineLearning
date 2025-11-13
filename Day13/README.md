    # 📧 Day 13 — Naive Bayes (Spam Classifier)

### 🎯 Objective
Build a Spam/Ham email classifier using the **Naive Bayes** algorithm and text vectorization (Bag of Words + TF-IDF).

---

## 📘 Concepts Covered
### 1. What is Naive Bayes?
A probabilistic classifier based on **Bayes’ Theorem**:

\[
P(A|B) = \frac{P(B|A) P(A)}{P(B)}
\]

For text:
- Each word contributes independently (naive assumption)
- Fast, accurate for spam detection, sentiment analysis, filtering

### 2. Variants
- **MultinomialNB** → Best for text (word frequencies)
- BernoulliNB → Binary features
- GaussianNB → Continuous features

---

## 🚀 Why Naive Bayes?
- Lightning fast
- Works amazingly well for text classification
- Requires very small training data
