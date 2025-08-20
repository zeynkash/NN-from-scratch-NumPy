# NN-from-scratch-NumPy
building Neural Network from scratch using NumPy, instead of relying on deep learning frameworks.

# Cat vs Non-Cat Classification 🐱🐶

This project implements a binary image classifier (cat vs non-cat) using a deep neural network from scratch with **NumPy**.  
It follows the exercises from Andrew Ng’s Deep Learning Specialization (Course 1: Neural Networks and Deep Learning).

---

## 📂 Project Structure
- `cat_vs_noncat.ipynb` → Jupyter Notebook with the full implementation  
- `train_catvnoncat.h5` → Training dataset (images + labels)  
- `test_catvnoncat.h5` → Test dataset (images + labels)

---

## 🚀 Features
- Load and preprocess `.h5` dataset (flatten + normalize images)  
- Implement forward and backward propagation from scratch  
- Train a deep L-layer neural network  
- Predict on new images  
- Evaluate model accuracy  

---

## ⚡ Requirements
- Python 3.x  
- NumPy  
- h5py  
- matplotlib  
- Jupyter Notebook (or Google Colab)

Install dependencies:
```bash
pip install numpy h5py matplotlib
