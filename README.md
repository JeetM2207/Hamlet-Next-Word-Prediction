# 📜 Hamlet Next Word Prediction using LSTM RNN

This project implements a **next-word prediction model** trained on Shakespeare's _Hamlet_ using an LSTM-based Recurrent Neural Network. It predicts the next word given a sequence of words, demonstrating how deep learning can model natural language patterns.

---

## 🧠 Objective

Train a deep learning model that can:
- Understand the style and language of Hamlet
- Predict the next word in a sequence
- Generate Shakespeare-like text

---

## 🧾 Dataset

- **Source**: [Project Gutenberg](https://www.gutenberg.org/)
- **Text Used**: *The Tragedy of Hamlet, Prince of Denmark* by William Shakespeare

---

## ⚙️ Technologies & Libraries

- Python 🐍
- TensorFlow / Keras
- NumPy
- NLTK (tokenization)
- Matplotlib (for plotting training metrics)

---

## 📁 Project Structure


---

## 🛠️ How It Works

1. **Data Preprocessing**:
   - Load Hamlet text and clean it
   - Tokenize the words using Keras Tokenizer
   - Create input sequences and corresponding next-word labels

2. **Model Architecture**:
   - Embedding Layer
   - LSTM Layer(s)
   - Dense Output Layer with Softmax

3. **Training**:
   - Loss: `categorical_crossentropy`
   - Optimizer: `adam`
   - Metric: `accuracy`

4. **Prediction**:
   - User enters a text prompt
   - Model returns likely next word(s)

---


