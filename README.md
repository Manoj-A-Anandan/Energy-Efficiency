# Energy-Efficient AI Model

## Overview
This repository contains a lightweight AI model designed to be **energy-efficient** while maintaining high performance. The model is implemented using TensorFlow/Keras and is optimized for reducing power consumption and resource usage.

## Key Features 🚀
- **Mixed Precision Training:** Uses `mixed_float16` to accelerate computations and lower power usage.
- **Early Stopping:** Prevents unnecessary training cycles to save energy.
- **Lightweight Model:** Uses a minimal architecture to reduce computational load.
- **Efficient Dataset Usage:** Trained on the **MNIST** dataset for quick and low-resource training.

## Model Architecture 🏗️
- **Input:** 28x28 grayscale images (MNIST dataset)
- **Hidden Layers:**
  - Dense(64, ReLU activation)
  - Dense(32, ReLU activation)
- **Output:** Dense(10, Softmax activation)
- **Optimizer:** Adam with learning rate `0.001`

## Setup & Usage 💻
### **1. Install Dependencies**
```sh
pip install tensorflow
```
### **2. Run the Model**
```sh
python model.py
```

## Results 📊
The model achieves high accuracy while consuming **less computational power**, making it suitable for sustainable AI applications.

## Why This Matters 🌍
With AI's growing energy demand, this project focuses on **responsible AI** by optimizing computation and reducing waste, aligning with sustainable AI principles.

---
🔗 **Feel free to contribute!** Open-source contributions are welcome to improve and refine this model further.
