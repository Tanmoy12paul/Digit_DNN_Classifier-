# Digit_DNN_Classifier

A DNN model to classify handwritten digits from the MNIST dataset.
---

## 🧠 Network Architecture

The model uses a fully connected (dense) architecture:

![DNN Architecture](https://github.com/Tanmoy12paul/Digit_DNN_Classifier-/blob/main/DNN_img/neural_net.png)

- **Input Layer**: 784 neurons (28x28 pixels)
- **Hidden Layers**: Three fully connected layers with ReLU activation
- **Output Layer**: 10 neurons (digits 0–9) with softmax activation

This architecture enables the network to learn complex hierarchical features from the image data.

---

## 🧾 Dataset

The MNIST dataset contains 60,000 training and 10,000 test images of handwritten digits, each of size 28x28 pixels in grayscale.

Example samples from the dataset:

![MNIST Dataset](https://raw.githubusercontent.com/Tanmoy12paul/Digit_DNN_Classifier-/main/DNN_img/mnist_dataset.png)

---

## 🔎 Sample Predictions

These predictions showcase how well the trained model performs on test samples:

![Predictions](https://github.com/Tanmoy12paul/Digit_DNN_Classifier-/blob/main/DNN_img/sample_prediction.png)

---

## 📈 Accuracy Over Epochs

Training and validation accuracy over time:

![Accuracy Plot](https://github.com/Tanmoy12paul/Digit_DNN_Classifier-/blob/main/DNN_img/accuracy_plot.png)

---

## 🛠️ Training Pipeline

1. **Data Preprocessing**: Normalize and reshape input data.
2. **Train/Test Split**: Separate data into training and validation sets.
3. **Model Building**: Define architecture with hidden layers and activations.
4. **Training**: Compile and train with dropout, L2 regularization, and early stopping.
5. **Evaluation**: Assess performance on test data.
6. **Deployment**: Ready model for use in inference applications.

---

## 🧪 Techniques Used

- **ReLU Activation**: Enables learning of complex non-linear patterns.
- **Dropout**: Randomly disables neurons to prevent overfitting (commonly between 0.2 to 0.5).
- **L2 Regularization**: Penalizes large weights to reduce overfitting (a form of weight decay).
- **EarlyStopping**: Stops training when validation loss stagnates, saving training time and avoiding overfitting.
- **Adam Optimizer**: Adaptive learning rate optimizer for faster convergence.
- **Categorical Crossentropy Loss**: For multi-class classification.

---

## 💡 Model Summary

- **Activation Functions**: ReLU (hidden layers), Softmax (output)
- **Optimizer**: Adam
- **Loss Function**: Categorical Crossentropy
- **Regularization**: L2 + Dropout
- **Early Stopping**: Enabled with patience strategy

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Tanmoy12paul/Digit_DNN_Classifier-.git
cd Digit_DNN_Classifier-
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
