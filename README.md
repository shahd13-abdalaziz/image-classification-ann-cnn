# 🧠 Image Classification using ANN & CNN (CIFAR-10)

## 📌 Overview
This project implements and compares two deep learning models:
- Artificial Neural Network (ANN)
- Convolutional Neural Network (CNN)

for image classification using the CIFAR-10 dataset.

---

## 📊 Dataset
We use the CIFAR-10 dataset from :contentReference[oaicite:1]{index=1}:

- 60,000 images
- 10 classes:
  airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck
- Image size: 32x32 RGB

---

## ⚙️ Tools & Technologies
- Python 🐍
- :contentReference[oaicite:2]{index=2}
- NumPy
- Matplotlib
- Scikit-learn
- Seaborn
- :contentReference[oaicite:3]{index=3}

---

## 🔬 Project Pipeline

### 1. Data Exploration
- Visualized sample images
- Checked dataset shape and labels

### 2. Data Preprocessing
- Normalized pixel values (0–1)

### 3. Data Splitting
- Training set
- Validation set
- Test set

---

## 🧠 Models

### 🔹 ANN
- Flatten layer
- Dense layers
- Softmax output

### 🔹 CNN
- Conv2D layers
- MaxPooling layers
- Dense layers

---

## 🚀 Training
- Optimizer: Adam
- Loss: Sparse Categorical Crossentropy
- EarlyStopping used to prevent overfitting

---

## 📈 Evaluation
- Confusion Matrix
- Classification Report
- Accuracy comparison

---

## 📊 Results
CNN outperformed ANN due to its ability to extract spatial features.

---

## 📌 Conclusion
CNN is more suitable for image classification tasks compared to ANN.

---

## 👨‍💻 Author
Neural Network Course Project
