# Digit_DNN_Classifier

A DNN model to classify handwritten digits from the MNIST dataset.
---

## 🧠 Network Architecture

The model uses a fully connected (dense) architecture:

![DNN Architecture](DNN_img/to/neural_net.png)

- Input Layer: 784 neurons (28x28 pixels)
- Hidden Layers: Two fully connected layers with ReLU activation and dropout regularization
- Output Layer: 10 neurons (digits 0–9)

---

## 🧾 Dataset

The MNIST dataset consists of 60,000 training and 10,000 test images of handwritten digits.

Example samples from the dataset:

![MNIST Dataset](DNN_img/to/mnist_dataset.png)

---

## 🔎 Sample Predictions

These predictions demonstrate how the trained model performs on test samples:

![Predictions](DNN_img/to/sample_prediction.png)

---

## 📈 Accuracy Over Epochs

The plot below shows training and validation accuracy per epoch, using dropout, L2 regularization, and early stopping:

![Accuracy Plot](DNN_img/to/accuracy_plot.png)

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/mnist-with-deep-neural-network.git
cd mnist-with-deep-neural-network
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the notebook

```bash
jupyter notebook mnist_usingDDN.ipynb
```

---

## 📊 Model Summary

- Activation: ReLU
- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Metrics: Accuracy
- Techniques: Dropout, L2 Regularization, EarlyStopping

---
