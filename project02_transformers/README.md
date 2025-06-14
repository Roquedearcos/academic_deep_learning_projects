# 🔢 Project 02 – Transformers for Sequence Sorting

This notebook explores the use of Transformer models to perform sequence-to-sequence learning on synthetic datasets. The task consists of sorting sequences of numbers written in natural language.

---

## 🧠 Objective

Given a random sequence of number words (e.g. `["ten", "forty-two", "three"]`), the model learns to predict the sorted sequence:  
`["three", "ten", "forty-two"]`.

This is achieved using a Transformer architecture trained on synthetically generated input-output pairs.

---

## 🧪 Dataset

- **Synthetic** sequences are generated at runtime.
- Input: a shuffled list of number words (e.g. "eight", "two", "fifteen").
- Target: the sorted version of the same list.
- Includes both training and test set generation.

---

## 🧠 Key Concepts

- Transformer Encoder-Decoder architecture
- Tokenization of natural number words
- Positional encoding
- Cross-entropy loss for sequence prediction
- Sequence padding and masking
- Greedy decoding for output generation

---

## ⚙️ Technologies

- Python 3.9+
- PyTorch
- TorchText or custom tokenizer
- Jupyter Notebook

---

## 🚀 How to Run

1. Open `transformers.ipynb` in Jupyter or Google Colab.
2. Run all cells to:
   - Generate synthetic dataset
   - Initialize and train the model
   - Evaluate results on test sequences

No external files are needed; everything is generated within the notebook.

---

## 📂 Files

- `transformers.ipynb` – Practice 4: Transformer model for sorting natural language sequences
- `README.md` – this file

---

## 📄 License

This notebook is for academic and learning purposes only.

