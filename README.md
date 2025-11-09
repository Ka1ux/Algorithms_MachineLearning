# 🤖 Essential Machine Learning Algorithms

## 📚 Overview

This repository serves as a reference for the most influential and widely used **Machine Learning (ML) algorithms**. The material is organized by learning paradigms, from classical statistical methods to cutting-edge **Deep Learning** architectures.

---

## I. 🔎 Supervised Learning

Models that learn to map input features $X$ to labeled output targets $y$. Used for **prediction**.

### 1. Linear & Logistic Regression

| Algorithm | Type | Core Function |
| :--- | :--- | :--- |
| **Linear Regression** | Regression | Finds the best line to predict a **continuous value** (e.g., price). |
| **Logistic Regression** | Classification | Uses the Sigmoid function to predict the **probability** of belonging to a class (e.g., Yes/No). |

### 2. Random Forest

#### 🌳 Concept
This is an **Ensemble** method that builds multiple **Decision Trees** (the forest) during training and outputs the class that is the mode (majority vote) of the classes for classification, or the average of predictions for regression. It's known for its **high accuracy** and robustness.

#### 🎯 Applications
Risk analysis, medical diagnosis, and any problem requiring high classification performance.

---

## II. 🧩 Unsupervised Learning

Models that discover patterns in **unlabeled data**. Used for **structure discovery**.

### 1. K-Means

#### ✨ Concept
A **clustering** algorithm that partitions the data into $K$ groups, where $K$ is a defined parameter. It minimizes the within-cluster variance by moving **centroids** until data points are closer to their own centroid than to others.

#### 🛒 Applications
**Customer segmentation**, document clustering by topic, image compression.

### 2. Autoencoder

#### 💡 Concept
A **Neural Network** architecture used to learn efficient representations of the input data (**encoding**), typically for dimensionality reduction. It has an **Encoder** (compresses) and a **Decoder** (reconstructs).

#### 🛡️ Applications
**Anomaly detection** (abnormal data is poorly reconstructed), unsupervised data compression.

---

## III. 🧠 Deep Learning

Models that use **multiple hidden layers** in Neural Networks to extract complex features.

### 1. MLP (Multi-Layer Perceptron)

#### 📉 Concept
The most basic **feed-forward neural network**. It is the foundation of all Deep Learning, consisting of connected neuron layers, trained via **Backpropagation**.

### 2. CNN (Convolutional Neural Network)

#### 🖼️ Concept
Specialized for grid-like data (images). It uses **Convolutional** and **Pooling Layers** to hierarchically learn **spatial features** (edges, textures) from the input.

#### 🚗 Applications
**Computer Vision**, facial recognition, autonomous vehicles.

### 3. LSTM (Long Short-Term Memory)

#### ⏳ Concept
A variation of the **Recurrent Neural Network (RNN)** that solves the **vanishing gradient** problem in long sequences. It uses **gates** (input, forget, output) to control the flow of information and maintain **long-term memory**.

#### 🗣️ Applications
**Time Series Forecasting**, speech processing, machine translation.

### 4. BERT (Bidirectional Encoder Representations from Transformers)

#### 💬 Concept
A language model based on the **Transformer** architecture. It is a **pre-trained** model that processes text **bidirectionally**, understanding a word's context based on all surrounding words simultaneously.

#### ❓ Applications
State-of-the-art **Natural Language Processing (NLP)**, question-answering systems.

---
