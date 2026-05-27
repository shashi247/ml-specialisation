# Advanced-Learning-Algorithms
Practical and learning algorithm the decision tree with variations of the decision tree, including random forests and boosted trees (XGBoost).
# 👋 Hi, I'm Shashi Kant Oraon

## 🚀 Product Manager | Aspiring Machine Learning Practitioner

I’m a **Product Manager at Vivo Mobiles India**, building and scaling **D2C e‑commerce platforms**. Alongside product strategy and execution, I actively invest in **Machine Learning fundamentals** to better design data‑driven products, personalization systems, pricing engines, and intelligent decision workflows.

---

## 🎓 Certifications

### ✅ Supervised Machine Learning: Regression and Classification

**Instructor:** Andrew Ng
**Platform:** Coursera
📜 **Credential:** [View Certificate / Course]([https://www.coursera.org/learn/machine-learning](https://coursera.org/share/8079cac9f1eb9c0f8e097cce5de31961)

This certification strengthened my understanding of core supervised learning techniques and the mathematical intuition behind them, with hands‑on implementation using Python.

---

## 📅 Week-wise Learning Objectives (Andrew Ng – Supervised Machine Learning & Neural Networks)

---

# 🧠 Neural Networks, Model Optimization, and Advanced ML Concepts

## 🗓️ Week 1: Neural Network Foundations

### 📚 Detailed Learning Objectives

* Understand neural network architecture: input, hidden, and output layers
* Learn how neurons connect using weights and biases
* Understand feature learning across layers
* Calculate activations using mathematical functions
* Build neural networks using TensorFlow and pure Python
* Understand vectorized computation for performance optimization

### 🧩 Neural Network Component Diagram

```
Input Layer      Hidden Layer         Output Layer
x₁ ───────▶  ○ ───────▶ ○ ───────▶ Prediction
x₂ ───────▶  ○ ───────▶ ○
x₃ ───────▶  ○ ───────▶ ○
```

### 🧮 Activation Calculation Formula

For neuron j:

zʲ = Σ(wᵢxᵢ) + b
aʲ = g(zʲ)

Vectorized form:

z = Wx + b
a = g(z)

---

### 🖼️ Image Classification Feature Learning

```
Input Image → Edge Detection → Shape Detection → Object Recognition

Layer 1 → Learns edges
Layer 2 → Learns shapes
Layer 3 → Learns objects
```

---

### ⚡ Vectorization (Parallel Processing)

Without vectorization:

Loop through each example

With vectorization:

Z = XW + b

Faster and scalable computation

---

## 🗓️ Week 2: Training Neural Networks & Activation Functions

### 📚 Detailed Learning Objectives

* Train neural networks using TensorFlow
* Understand activation function selection
* Implement multiclass classification
* Apply softmax and categorical cross entropy

### ⚡ Activation Functions Mathematical Forms

Sigmoid:

σ(z) = 1 / (1 + e⁻ᶻ)

ReLU:

ReLU(z) = max(0, z)

Linear:

f(z) = z

---

### 🌐 Softmax Function

Used for multiclass classification:

softmax(zᵢ) = e^zᵢ / Σ e^zⱼ

Example Output:

```
Class A → 0.75
Class B → 0.15
Class C → 0.10
```

---

### 📉 Categorical Cross Entropy Loss

J = − Σ yᵢ log(ŷᵢ)

Measures prediction error.

---

## 🗓️ Week 3: Model Evaluation and Improvement

### 📚 Detailed Learning Objectives

* Evaluate models using validation and test datasets
* Diagnose bias and variance issues
* Apply regularization
* Improve performance using transfer learning
* Use precision and recall metrics

---

### 📊 Dataset Splitting

```
Full Dataset
   │
   ├── Training Set
   ├── Validation Set
   └── Test Set
```

---

### 📉 Regularization Formula

L2 Regularization:

J = Loss + (λ/2m) ΣW²

Prevents overfitting.

---

### 📊 Precision and Recall

Precision = TP / (TP + FP)

Recall = TP / (TP + FN)

```
High Precision → Few False Positives
High Recall → Few False Negatives
```

---

### 🔁 ML Development Iteration Loop

```
Train → Evaluate → Diagnose → Improve → Retrain
```

---

## 🗓️ Week 4: Decision Trees and Ensemble Methods

### 📚 Detailed Learning Objectives

* Understand decision tree structure and prediction logic
* Learn entropy and impurity calculation
* Understand ensemble methods: Random Forest and Boosting
* Compare neural networks vs decision trees

---

### 🌳 Decision Tree Prediction Flow

```
        Feature?
        /     \
     Yes       No
     /           \
  Predict A    Predict B
```

---

### 📉 Entropy Formula

Entropy = − Σ p log₂(p)

Where:

* p = probability of class

Lower entropy = better classification split

---

### 🌲 Random Forest Ensemble

```
Tree 1 → Prediction A
Tree 2 → Prediction B
Tree 3 → Prediction A

Final Prediction → Majority Vote
```

---

### ⚖️ When to Use Each Model

Neural Networks → Images, speech, complex patterns
Decision Trees → Structured data, interpretability

---

### 🎯 Key Concepts

* Structure and components of neural networks
* Layers, neurons, weights, and biases
* Forward propagation and activation computation
* Image classification using neural networks
* Implementing neural networks using TensorFlow and Python

---

### 🧩 Neural Network Architecture

```
Input Layer        Hidden Layer         Output Layer
(x₁, x₂, x₃)  →   (a₁, a₂, a₃)   →     (ŷ)

Each connection has:
Weight (w)
Bias (b)
```

Mathematical Representation:

z = w·x + b
a = g(z)

Where:

* x = input features
* w = weights
* b = bias
* g(z) = activation function
* a = activation output

---

### 🔄 Forward Propagation

```
z¹ = W¹x + b¹
a¹ = g(z¹)

z² = W²a¹ + b²
ŷ = g(z²)
```

This process transforms inputs into predictions.

---

### 🖼️ Neural Network for Image Classification

```
Image Pixels → Hidden Layers → Feature Learning → Classification

Example:
Image → Edge Detection → Shape Detection → Object Classification
```

---

## 🗓️ Week 2: Training Neural Networks & Activation Functions

### 🎯 Key Concepts

* Training neural networks using TensorFlow
* Activation functions: Sigmoid, ReLU, Linear
* Multiclass classification using Softmax
* Cross-entropy loss

---

### ⚡ Activation Functions

#### Sigmoid

σ(z) = 1 / (1 + e⁻ᶻ)

Used for:

* Binary classification output layer

```
     ______
   /
 /
/__________
```

---

#### ReLU (Rectified Linear Unit)

ReLU(z) = max(0, z)

Used for:

* Hidden layers

```
    /
   /
  /
_/________
```

---

### 🌐 Softmax for Multiclass Classification

Softmax formula:

P(y=i) = e^zi / Σ e^zj

Example Output:

```
Cat   → 0.7
Dog   → 0.2
Bird  → 0.1
```

---

### 📉 Cross Entropy Loss

J = − Σ y log(ŷ)

Used to measure classification error.

---

## 🗓️ Week 3: Improving Model Performance

### 🎯 Key Concepts

* Cross validation and test sets
* Bias vs Variance diagnosis
* Regularization
* Error analysis
* Transfer learning
* Data augmentation
* Fairness and ethics

---

### 📊 Bias vs Variance

```
Underfit        Good Fit         Overfit
   /              __              _/\_
  /              /  \            /    \
```

High Bias → Model too simple
High Variance → Model too complex

---

### 📉 Regularization

Regularized Cost Function:

J = original loss + (λ/2m) ΣW²

Purpose:

* Prevent overfitting
* Improve generalization

---

### 🔁 Machine Learning Development Cycle

```
Train Model
    ↓
Evaluate
    ↓
Error Analysis
    ↓
Improve Data / Model
    ↓
Repeat
```

---

### 📊 Precision and Recall

Precision = TP / (TP + FP)

Recall = TP / (TP + FN)

Used for imbalanced datasets.

---

## 🗓️ Week 4: Decision Trees and Ensemble Methods

### 🎯 Key Concepts

* Decision tree structure
* Entropy and impurity
* Random Forest and Boosted Trees
* When to use neural networks vs trees

---

### 🌳 Decision Tree Structure

```
        Age?
       /    \
     <30    ≥30
     /        \
  Buy       Income?
            /     \
         High     Low
         Buy     No Buy
```

---

### 📉 Entropy Formula

Entropy measures impurity:

H(p) = − Σ p log₂(p)

Lower entropy = better split

---

### 🌲 Random Forest

```
Tree 1 → Prediction
Tree 2 → Prediction
Tree 3 → Prediction

Final Prediction → Average / Majority Vote
```

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
