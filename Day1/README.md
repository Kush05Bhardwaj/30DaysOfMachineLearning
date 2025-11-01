# 🧠 Day 01 — Introduction to Machine Learning

## 🎯 Aim / Learning Objective
Understand what Machine Learning is, its core types, workflow, and how it fits into the broader AI ecosystem.

---

## 📘 1. What is Machine Learning?
Machine Learning (ML) is a subset of Artificial Intelligence that allows systems to **learn patterns from data** and make predictions or decisions **without being explicitly programmed**.

In ML, we don’t write specific rules — instead, the model learns from examples.

> 🧩 Example:  
> Instead of coding "what a cat looks like," we give the model thousands of cat images — it learns to recognize patterns automatically.

---

## 🤖 2. AI vs ML vs DL

| Concept | Description | Example |
|----------|--------------|----------|
| **AI (Artificial Intelligence)** | Broad field focused on creating intelligent systems that can simulate human behavior. | Chess-playing bot |
| **ML (Machine Learning)** | Subset of AI where systems learn from data. | Email spam filter |
| **DL (Deep Learning)** | Subset of ML using neural networks with multiple layers. | Image recognition using CNNs |

🧠 **Hierarchy:**  
**AI ⊃ ML ⊃ DL**

---

## 🧩 3. Types of Machine Learning

| Type | Description | Example |
|------|--------------|----------|
| **Supervised Learning** | Model learns from labeled data. | Predicting house prices |
| **Unsupervised Learning** | Model finds hidden patterns in unlabeled data. | Customer segmentation |
| **Reinforcement Learning** | Agent learns by interacting with an environment using rewards/punishments. | Self-driving car learning to stay in lane |

---

## ⚙️ 4. Machine Learning Workflow

1. **Data Collection** → Gather relevant data  
2. **Data Preprocessing** → Clean, scale, handle missing values  
3. **Model Training** → Feed processed data into algorithm  
4. **Evaluation** → Measure model performance (accuracy, precision, etc.)  
5. **Deployment** → Integrate model into real-world use  
6. **Monitoring** → Track performance over time  

📈 **Example:**  
You collect house price data → train regression model → test → deploy → monitor predictions.

---

## 🧰 5. Tools will be using
- **Python** (core language)
- **NumPy & Pandas** (data manipulation)
- **Matplotlib / Seaborn** (visualization)
- **Scikit-learn (sklearn)** (ML algorithms)
- **Jupyter Notebook** (experimentation)

---

## 💻 6. Small Practice Task

Create a Python file or notebook (`ml_intro.ipynb`) and write:

```python
import sklearn
print("Scikit-learn version:", sklearn.__version__)
```

---