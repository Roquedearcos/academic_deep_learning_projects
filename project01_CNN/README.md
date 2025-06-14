# 🧠 Project 01 – Neural Network & CNN Classifiers

This directory contains two academic notebooks from the Neural Networks and Deep Learning course. Both projects focus on image classification using the MNIST dataset, progressing from a basic neural network to a convolutional model with transfer learning.

---

## 📓 P1: Neural Network Classifier (`NN_cls.ipynb`)

In this notebook, we build a simple neural network using PyTorch to classify handwritten digits from the MNIST dataset.  
Each image is a 28x28 grayscale image representing a digit from 0 to 9.

### 🧠 Key Concepts
- Fully connected layers (`nn.Linear`)
- Activation functions (e.g., ReLU)
- CrossEntropyLoss for classification
- Data loading with `torchvision.datasets.MNIST`

### 🎯 Objective
Train a model that accurately predicts the digit in each image using supervised learning.

---

## 📓 P2: CNN + Transfer Learning (`CNN_cls.ipynb`)

This notebook implements a CNN-based image classifier using **transfer learning**.  
We load a pretrained model (e.g., ResNet or VGG) trained on ImageNet, and adapt only its final layer to classify MNIST digits.

### 🧠 Key Concepts
- Convolutional Neural Networks (CNN)
- Feature extraction from pretrained models
- Freezing layers and modifying output layers
- Training on GPU (recommended in Google Colab)

---
## 📁 Data

The MNIST dataset is automatically downloaded and stored in the `data/` directory when using `torchvision.datasets.MNIST`.  
No manual download is required.

---

## 📂 Files

- `NN_cls.ipynb` – Practice 1: basic neural network
- `CNN_cls.ipynb` – Practice 2: CNN with transfer learning
- `README.md` – this file

---

## 📄 License

These notebooks are for academic and learning purposes only.

