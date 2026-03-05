# Mnist Digit Recognition with CNN 🖥️

Welcome to this **MNIST CNN project**! This project demonstrates how to classify handwritten digits (0–9) using a **Convolutional Neural Network (CNN)** built with **TensorFlow & Keras**.  

---

## 🧾 Project Overview

This project covers:

- Loading and exploring the **MNIST dataset** 📊  
- Preprocessing images for CNN input 🔄  
- Building a **CNN model** for digit classification 🏗️  
- Training the model and monitoring **accuracy & loss** 📈  
- Evaluating model performance using:
  - Confusion Matrix 🧩  
  - Classification Report 📄  
  - Precision & Recall per digit 🎯  
  - ROC curves & AUC for each digit 📊  
  - Top-3 accuracy 💡  
- Visualizing:
  - Sample digits 🖼️  
  - Misclassified images ❌  
  - CNN activations for first convolutional layer 🔬  
- Testing robustness on **noisy images** 🌪️  

---

## ⚙️ Technologies & Libraries

- **Python 3** 🐍  
- **TensorFlow / Keras** 🔥  
- **NumPy** for numerical operations 🧮  
- **Matplotlib & Seaborn** for visualizations 🎨  
- **Scikit-learn** for metrics 📊  

---
## 🏗️ Model Architecture

Our CNN model includes:

- **Input Layer**: 28×28×1 images 🖼️
- **Conv2D Layer 1**: 32 filters, 3×3 kernel, ReLU activation
- **MaxPooling Layer 1**: 2×2 pooling
- **Conv2D Layer 2**: 64 filters, 3×3 kernel, ReLU activation
- **MaxPooling Layer 2**: 2×2 pooling
- **Flatten Layer**
- **Dense Layer**: 64 neurons, ReLU activation
- **Output Layer**: 10 neurons, softmax activation 🟢
**Optimizer:** Adam  
**Loss Function:** Sparse Categorical Crossentropy  
**Metrics:** Accuracy ✅
--------
## 🚀 Results

- **Test Accuracy:** ~99% (after longer training)  
- **Top-3 Accuracy:** ~99.7%  
- **Robustness:** Model is robust to noisy images with minor performance drop 🌪️

------

## 📦 Installation

Install the required libraries via pip:

```bash
pip install tensorflow numpy matplotlib seaborn scikit-learn pandas


