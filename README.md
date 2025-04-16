# 🧠 Logistic Regression from Scratch with Custom Optimizers

This project implements **Logistic Regression from scratch using NumPy** for binary classification. It includes three optimization techniques — **Batch Gradient Descent**, **Stochastic Gradient Descent**, and **Mini-Batch Gradient Descent** — all written manually (no external ML libraries like TensorFlow or scikit-learn models).

> 🎯 The goal is to provide a **clear understanding** of how logistic regression and its training optimizers work under the hood.

---

## 🚀 Features

- ✅ Logistic Regression for binary classification
- 🔁 Custom implementations of:
  - Batch Gradient Descent
  - Stochastic Gradient Descent (SGD)
  - Mini-Batch Gradient Descent
- 📊 Real-time loss tracking and plotting
- 📈 Evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - Confusion Matrix
- 🧪 Synthetic dataset generation using scikit-learn

---

## 📂 Project Structure

```
├── logistic_regression.py      # Main implementation
├── README.md                   # Project overview
```

---

## 📌 Requirements

- Python 3.x
- numpy
- matplotlib
- scikit-learn

Install dependencies using:

```bash
pip install numpy matplotlib scikit-learn
```

---

## 🧪 How It Works

1. A synthetic binary classification dataset is generated using `make_classification`.
2. The dataset is split into training and testing sets.
3. Logistic Regression is trained using one of the selected optimizers.
4. Loss is printed and tracked per epoch.
5. The model is evaluated using classification metrics.
6. A graph comparing the loss curves of different optimizers is plotted.

---

## ⚙️ Usage

Simply run the script:

```bash
python logistic_regression.py
```

---

## 📈 Output Example

- Console:
  ```
  Training with batch gradient descent
  Epoch 1/50 - Loss: 0.6932
  ...
  Accuracy: 0.8750
  Precision: 0.86
  Recall: 0.89
  F1 Score: 0.87
  ```

- Visual:
  - A plot comparing the loss curves of batch, stochastic, and mini-batch optimizers.
