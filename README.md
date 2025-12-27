![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-orange)
![Unsupervised Learning](https://img.shields.io/badge/Unsupervised-Learning-purple)
![SOM](https://img.shields.io/badge/Algorithm-SOM-green)
![Healthcare](https://img.shields.io/badge/Application-Healthcare-red)

# 🧠 Self-Organizing Map (SOM) — Patient Classification

This project implements a **Kohonen Self-Organizing Map (SOM)** in Python to classify time-series marker data from healthy and patient subjects. It compares SOM with other machine learning methods (K-Means and k-Nearest Neighbors) and performs predictions on unseen test data.

---

## 🔍 Test Result: Hussain Dataset

| Sample        | Prediction |
|---------------|------------|
| Hussain #1    | Patient    |
| Hussain #2    | Patient    |
| Hussain #3    | Patient    |
| Hussain #4    | Patient    |

---

## 📊 SOM vs. Other Algorithms

### 1. SOM vs. K-Means

| Feature             | SOM                            | K-Means                          |
|---------------------|--------------------------------|----------------------------------|
| Topology Preservation | ✅ Preserves spatial structure | ❌ No topological structure      |
| Learning Mechanism  | Competitive learning with neighborhood | Centroid averaging        |
| Output Structure    | Structured 2D grid of neurons  | Flat cluster assignments         |

> Resources:
> - [K-Means and SOM - DZone](https://dzone.com/articles/k-means-and-som-gentle-introduction-to-worlds-most)
> - [Comparative analysis (IEEE)](https://ieeexplore.ieee.org/document/5492838)

### 2. SOM vs. k-NN

| Feature            | SOM                         | k-Nearest Neighbors (k-NN)       |
|--------------------|-----------------------------|----------------------------------|
| Supervision        | ❌ Unsupervised              | ✅ Supervised                     |
| Purpose            | Clustering, Visualization   | Classification                   |
| Model              | Trained neuron map          | Lazy learning (no training)      |

> Reference:
> - [Comparison with k-NN (IEEE)](https://ieeexplore.ieee.org/document/7059477)

---

## 🛠️ Implementation Steps

### Step 1: Load and Label Data
### Step 2: Train the SOM

### Step 3: Assign Neuron Labels via Majority Voting
### Step 4: Predict Class for New Sample

## 🧠 Summary
SOM is ideal for exploring and clustering high-dimensional medical data. It provides a visual and interpretable map that outperforms basic clustering when structure matters.


