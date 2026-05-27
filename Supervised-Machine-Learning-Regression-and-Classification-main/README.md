# 👋 Hi, I'm Shashi Kant Oraon

## 🚀 Product Manager | Aspiring Machine Learning Practitioner

I’m a **Product Manager at leading smartphone OEM**, building and scaling **D2C e‑commerce platforms**. Alongside product strategy and execution, I actively invest in **Machine Learning fundamentals** to better design data‑driven products, personalization systems, pricing engines, and intelligent decision workflows.

---

## 🎓 Certifications

### ✅ Supervised Machine Learning: Regression and Classification

**Instructor:** Andrew Ng
**Platform:** Coursera
📜 **Credential:** [View Certificate / Course](https://coursera.org/share/4ac4e79290e7e628f2b59eb273e3a7db)

This certification strengthened my understanding of core supervised learning techniques and the mathematical intuition behind them, with hands‑on implementation using Python.

---

## 📅 Week-wise Learning Objectives (Andrew Ng – Supervised Machine Learning)

### 🗓️ Week 1: Foundations of Machine Learning & Linear Regression

**Key Objectives**

* Understand what Machine Learning is and when to use it
* Differentiate between supervised and unsupervised learning
* Write and execute Python code using Jupyter Notebooks
* Build intuition for regression models
* Implement cost functions and gradient descent from scratch

**Conceptual Overview**

```
Data (X, y)
   │
   ▼
Hypothesis f(x)
   │
   ▼
Prediction (ŷ)
   │
   ▼
Cost Function J(w,b)
   │
   ▼
Gradient Descent → Updated Parameters
```

**Supervised vs Unsupervised Learning**

```
Supervised Learning        Unsupervised Learning
(X, y) labeled             X only (no labels)
│                          │
▼                          ▼
Regression / Classification  Clustering / Dim. Reduction
```

**Linear Regression Model**

ŷ = wx + b

**Cost Function (Mean Squared Error)**

J(w,b) = (1/2m) Σ(ŷ − y)²

**Gradient Descent Updates**

w := w − α ∂J/∂w
b := b − α ∂J/∂b

```
Cost
 ▲          •
 |        •
 |      •
 |    •
 |  •
 |•________________▶ w
```

---

### 🗓️ Week 2: Multiple Linear Regression & Feature Engineering

**Key Objectives**

* Implement multiple linear regression using vectorization
* Apply feature scaling for faster convergence
* Perform feature engineering and polynomial regression

**Multiple Linear Regression**

ŷ = w₁x₁ + w₂x₂ + ... + wₙxₙ + b

**Vectorized Form**

ŷ = Xw + b

**Feature Scaling (Standardization)**

x_scaled = (x − μ) / σ

**Polynomial Regression**

ŷ = w₁x + w₂x² + w₃x³ + b

---

### 🗓️ Week 3: Classification, Logistic Regression & Regularization

**Key Objectives**

* Solve binary classification problems
* Implement logistic regression
* Address overfitting using regularization

**Logistic Regression**

ŷ = σ(z),  z = wᵀx + b

σ(z) = 1 / (1 + e⁻ᶻ)

**Binary Cross-Entropy Loss**

J = −(1/m) Σ[y log(ŷ) + (1 − y) log(1 − ŷ)]

**Regularization (L2)**

J = original cost + (λ/2m) Σw²

---

## 🧠 Machine Learning Concepts I’ve Learned

### 🔹 Supervised Learning

Learning a function **f(x) → y** from labeled data.

```
Input (X)  ──▶  Model  ──▶  Prediction (ŷ)
                │
                ▼
             Loss
                │
                ▼
          Parameter Update
```

---

### 📈 Regression

Used to predict **continuous values** such as revenue, demand, or delivery time.

**Examples:**

* Sales forecasting
* Price elasticity modeling
* Demand prediction

**Linear Regression Flow:**

```
y = w₁x₁ + w₂x₂ + ... + b

Cost Function (MSE):
J(w,b) = (1/2m) Σ (ŷᵢ − yᵢ)²
```

---

### 🏷️ Classification

Used to predict **discrete labels**.

**Examples:**

* Fraud detection (Yes / No)
* Customer churn (Churn / Retain)
* Lead qualification

**Logistic Regression Pipeline:**

```
Linear Combination → Sigmoid → Probability → Class

z = w·x + b
σ(z) = 1 / (1 + e⁻ᶻ)
```

---

### 📉 Gradient Descent

An optimization algorithm to minimize the cost function.

```
Repeat until convergence:
  w = w − α ∂J/∂w
  b = b − α ∂J/∂b
```

```
Cost
 ▲
 |        •
 |      •
 |    •
 |  •
 |•________________▶ Parameters
```

---

### 🧪 Model Evaluation

Key metrics depending on problem type:

* **Regression:** MSE, RMSE, R²
* **Classification:** Accuracy, Precision, Recall

```
Train Set ─▶ Model ─▶ Validate ─▶ Improve
```

---

## 🛠️ Tools & Skills

* **Languages:** Python
* **Libraries:** NumPy, Pandas, Matplotlib
* **ML Concepts:**

  * Linear & Logistic Regression
  * Cost Functions
  * Gradient Descent
  * Feature Scaling
  * Bias vs Variance

---

## 📦 How I Apply ML Thinking as a Product Manager

* Designing **data‑backed experimentation frameworks**
* Translating business problems into **ML‑solvable use cases**
* Collaborating effectively with **Data Science & Engineering teams**
* Evaluating model impact using **product metrics & ROI**

---

## 🌱 What I’m Learning Next

* Advanced ML algorithms
* Feature engineering at scale
* Model deployment & monitoring
* ML use‑cases in **Payments, Pricing & Personalization**

---

📫 **Let’s connect and build intelligent products!**

> *“Machine learning is not about replacing decision‑makers, it’s about empowering them.”*
