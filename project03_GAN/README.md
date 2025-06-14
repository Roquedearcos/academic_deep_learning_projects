# 🧪 Project 03 – Generative Adversarial Networks (GAN)

This notebook implements a Generative Adversarial Network (GAN) using PyTorch to generate handwritten digit images similar to those in the MNIST dataset. The task focuses on conditional generation, where the GAN learns to produce digits corresponding to a given class label.

---

## 🧠 Objective

Train a conditional GAN that, given a target digit (e.g. "7"), generates realistic images of that digit based on the MNIST dataset. The generator learns to produce images, and the discriminator learns to distinguish between real and fake ones.

---

## 📊 Dataset

- **MNIST**: A dataset of 28x28 grayscale images of handwritten digits (0–9).
- Automatically downloaded using `torchvision.datasets.MNIST`.

---

## 🧠 Key Concepts

- GAN architecture: Generator and Discriminator
- Conditional generation (digit label as input)
- Latent vector sampling
- Binary Cross-Entropy Loss (BCE)
- Training stability and alternating updates

---

## ⚙️ Technologies

- Python 3.9+
- PyTorch
- torchvision
- matplotlib (for image visualization)
- Jupyter Notebook

---

## 🚀 How to Run

1. Open `GAN.ipynb` in Jupyter or Google Colab.
2. Run all cells to:
   - Load MNIST dataset
   - Initialize generator and discriminator models
   - Train the GAN
   - Visualize generated samples during and after training

Make sure GPU is enabled if running in Colab for faster training.

---

## 📂 Files

- `GAN.ipynb` – Practice 5: Conditional GAN on MNIST
- `README.md` – this file

---

## 📄 License

This notebook is for academic and learning purposes only.

