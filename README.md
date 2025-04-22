# 🧠 MNIST Feedforward Neural Network

This is a flexible implementation of a **feedforward neural network** using **PyTorch**, built for CBIT's Deep Learning Assignment 1. The network is trained on the **MNIST** dataset and supports multiple optimizers, activation functions, and hyperparameters.

---

## 📁 Project Structure

. ├── main.py # Entry point to train and evaluate model ├── model.py # Customizable neural network architecture ├── train.py # Training + validation logic ├── requirements.txt # Required packages └── README.md # Project instructions

yaml
Copy
Edit

---

## ⚙️ Features

- ✅ Custom hidden layers (3, 4, 5 layers)
- ✅ Flexible neuron count (32, 64, 128 per layer)
- ✅ Activation functions: ReLU / Sigmoid
- ✅ Optimizers: `sgd`, `momentum`, `nesterov`, `rmsprop`, `adam`, `nadam`
- ✅ Hyperparameter tuning support (batch size, learning rate, weight decay)
- ✅ Train/Validation/Test split (90/10/10)
- ✅ Accuracy evaluation on validation + test set

---

## 🔧 Setup & Run

1. **Install packages:**
   ```bash
   pip install -r requirements.txt
Train the model:

bash
Copy
Edit
python main.py
📊 Evaluation
Uses CrossEntropyLoss

Accuracy printed per epoch

Supports comparison with MSELoss (optional)

Confusion matrix plotting (optional)

📌 Assignment Info
📚 Subject: Deep Learning (22CAC04)

🧑‍🎓 Roll No: 143

📁 Dataset: MNIST

🧪 Goal: Build and train a feedforward neural network using backpropagation
