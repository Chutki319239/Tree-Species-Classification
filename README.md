# 🌿 Tree Species Classification

> Project done during **AICTE Green Skills Shell Internship**

This project involves building a Convolutional Neural Network (CNN) to classify tree species based on images of their leaves.

---

## 📂 Dataset

- Dataset used: Tree leaf images categorized by species.
- Folder structure:
  
tree_dataset_split/
├── training/
│ ├── Guava/
│ ├── Mango/
│ └── ...
└── validation/
├── Guava/
├── Mango/
└── ...

- Source: [Kaggle Dataset - Tree Species]
  Uploaded on Google Drive . Link below:
  https://drive.google.com/drive/folders/13wbL1FyAqXqMy419cYY70jyON8DmwdGp?usp=drive_link

---

## 🧠 Model Overview

- Built using **TensorFlow** and **Keras**
- Architecture: 3× Conv2D layers → MaxPooling → Flatten → Dense → Dropout → Output layer
- Optimizer: Adam
- Loss: Categorical Crossentropy
- Accuracy: ~90% on validation set

---

💾 Model Download
GitHub doesn’t allow uploads over 10MB.

Download trained .keras model from Google Drive:
👉https://drive.google.com/file/d/1r4kK4S9b7UPikALebqkuu4SHL2owQ_OP/view?usp=drive_link

📌 Requirements

Python ≥ 3.7
TensorFlow
Keras
NumPy
Matplotlib
