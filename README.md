# 🧠 MNIST & Fashion MNIST Image Classification using Neural Networks

## 📌 Overview

This project demonstrates image classification using deep learning models built with TensorFlow and Keras. It includes:

- 🔢 **MNIST Digit Classification** – Classifies handwritten digits (0–9)
- 👕 **Fashion MNIST Classification** – Classifies clothing items like shirts, trousers, sneakers, etc.

Each model is implemented in a dedicated Jupyter notebook. These projects showcase neural network training pipelines including data preprocessing, model construction, evaluation, and performance visualization.

---

## 📁 Folder Structure

mnist-fmnist-digit-classification/
│
├── mnist_digit/
│   └── digit_classifier.ipynb              # Handwritten digit classifier
│
├── fashion_mnist/
│   └── fashion_classifier.ipynb            # Fashion item classifier
│
├── requirements.txt                        # List of Python dependencies
├── README.md                               # Project documentation
└── LICENSE                                 # MIT License

---

## 📊 Datasets Used

### 🟦 MNIST (Handwritten Digits)
- 60,000 training images + 10,000 testing images
- Each image is a 28x28 grayscale digit from 0 to 9

### 🟪 Fashion MNIST (Clothing Items)
- 60,000 training images + 10,000 testing images
- Classes: T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot

---

## 🧠 Models & Methodology

### 🧮 Digit Classifier
- **Input:** 28x28 normalized grayscale image
- **Model:** Dense neural network with hidden layers
- **Output:** 10-class softmax layer
- **Loss Function:** Categorical crossentropy
- **Optimizer:** Adam
- **Accuracy:** ~97% on test data

### 👕 Fashion Classifier
- **Input:** 28x28 normalized grayscale image
- **Model:** Dense layers + Dropout regularization
- **Output:** 10-class softmax layer
- **Loss Function:** Categorical crossentropy
- **Optimizer:** Adam
- **Accuracy:** ~90% on test data

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

