# Artificial Neural Network (ANN) for Breast Cancer Classification

This project demonstrates how to build, train, and evaluate an Artificial Neural Network (ANN) using Keras to classify breast cancer tumors as malignant or benign.

---

## Problem Statement

Early detection of breast cancer can significantly improve survival rates.  
In this project, we use machine learning to classify tumors based on diagnostic features.

Dataset used:
- sklearn.datasets.load_breast_cancer

---

## Tech Stack

- Python
- TensorFlow / Keras
- Scikit-learn
- Matplotlib
- keras-visualizer

---

## Model Architecture

- Input Layer  
- Dense Layers with ReLU activation  
- Batch Normalization  
- Dropout (regularization)  
- Output Layer (Sigmoid for binary classification)  

---

## Key Concepts Demonstrated

- Data preprocessing  
- Train-test split  
- Neural network architecture design  
- Weight initialization (He Normal)  
- Batch Normalization  
- Dropout for overfitting prevention  
- EarlyStopping & ModelCheckpoint  
- Loss function: Binary Crossentropy  
- Optimizer: SGD  

---

## Training Strategy

- Early stopping to prevent overfitting  
- Validation monitoring  
- Efficient convergence using proper initialization  

---

## How to Run

```bash
git clone https://github.com/your-username/ann-classification-breast-cancer-keras.git
cd ann-classification-breast-cancer-keras
pip install -r requirements.txt
jupyter notebook
```

---

## Future Improvements

- Add hyperparameter tuning  
- Try different optimizers (Adam, RMSprop)  
- Convert into modular Python scripts  
- Deploy using Streamlit  

---

## Author

Damodaran Selvaraj
