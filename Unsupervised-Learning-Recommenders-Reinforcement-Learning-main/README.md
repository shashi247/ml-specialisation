# 👋 Hi, I'm Shashi Kant Oraon

## 🚀 Product Manager | Aspiring Machine Learning Practitioner

I’m a **Product Manager at Vivo Mobiles India**, building and scaling **D2C e‑commerce platforms**. Alongside product strategy and execution, I actively invest in **Machine Learning fundamentals** to better design data‑driven products, personalization systems, pricing engines, and intelligent decision workflows.

---

## 🎓 Certifications

### ✅ Supervised Machine Learning: Regression and Classification

**Instructor:** Andrew Ng
**Platform:** Coursera
📜 **Credential:** [View Certificate / Course]([https://www.coursera.org/learn/machine-learning](https://coursera.org/share/b166789be1ceea714c674eb4b4fba832))

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

# 🤖 Unsupervised Learning, Recommender Systems, and Reinforcement Learning

## 🗓️ Week 1: K-Means Clustering and Anomaly Detection

### 📚 Detailed Learning Objectives

* Implement K-means clustering algorithm
* Define and optimize clustering objective function
* Initialize centroids and update them iteratively
* Select optimal number of clusters (K)
* Implement anomaly detection system
* Decide when to use supervised vs anomaly detection

---

### 🌐 K-Means Clustering Algorithm Flow

```
Step 1: Initialize centroids randomly
Step 2: Assign each point to closest centroid
Step 3: Update centroids (mean of assigned points)
Step 4: Repeat until convergence
```

Illustration:

```
Cluster 1        Cluster 2
   ● ● ●            ▲ ▲ ▲
     ●                ▲
   Centroid        Centroid
```

---

### 🧮 K-Means Optimization Objective Function

Goal: Minimize distance between points and assigned centroid

J = (1/m) Σ ||x⁽ⁱ⁾ − μ_c⁽ⁱ⁾||²

Where:

* x⁽ⁱ⁾ = data point
* μ_c⁽ⁱ⁾ = centroid of assigned cluster

---

### 📍 Finding Closest Centroid

Distance formula:

||x − μ||² = Σ (xⱼ − μⱼ)²

Assign to cluster with minimum distance.

---

### 🔄 Centroid Update Function

New centroid = Mean of assigned points

μ_k = (1/n) Σ x⁽ⁱ⁾

---

### 🚨 Anomaly Detection

Used when anomalies are rare.

Gaussian Distribution:

p(x) = (1 / √(2πσ²)) e^(−(x−μ)² / 2σ²)

If probability is very low → anomaly

```
Normal Data → High probability
Anomaly → Low probability
```

---

### ⚖️ Supervised Learning vs Anomaly Detection

```
Supervised Learning → Many labeled examples
Anomaly Detection → Few anomaly examples
```

---

## 🗓️ Week 2: Recommender Systems

### 📚 Detailed Learning Objectives

* Implement collaborative filtering
* Build neural network based recommender systems
* Learn ethical considerations

---

### 🎯 Collaborative Filtering Concept

Goal: Predict user preference

Prediction formula:

ŷ(i,j) = w(j) · x(i) + b

Where:

* w(j) = user vector
* x(i) = item vector

Illustration:

```
User Features × Movie Features → Rating Prediction
```

Matrix Form:

R ≈ XWᵀ

---

### 🧠 Neural Network Recommender

```
User Features → Neural Network → Embedding
Item Features → Neural Network → Embedding

Similarity → Recommendation
```

---

### ⚖️ Ethics in Recommender Systems

Considerations:

* Bias
* Fairness
* Transparency
* Privacy

---

## 🗓️ Week 3: Reinforcement Learning and Deep Q Learning

### 📚 Detailed Learning Objectives

* Understand RL terminology
* Learn Bellman equation
* Build deep Q-learning model

---

### 🧩 Reinforcement Learning Components

```
Agent → takes Action → Environment
Environment → returns Reward + State
```

Key Terms:

State (S) → Current situation
Action (A) → Decision taken
Reward (R) → Feedback
Policy (π) → Strategy

---

### 🧮 Bellman Equation

Q(s,a) = R(s,a) + γ max Q(s',a')

Where:

* Q(s,a) = value of action
* γ = discount factor

---

### 🧠 Deep Q Network Architecture

```
State → Neural Network → Q Values → Best Action
```

Mathematical Form:

Q(s,a; θ) ≈ Neural Network

---

### 🔁 Reinforcement Learning Loop

```
State → Action → Reward → New State → Learn → Improve
```

---

## 🧠 Machine Learning Concepts I’ve Learned
