# 🧠 Breast Cancer Prediction — Deep Learning Model

## 📌 Overview
This project implements a **binary classification model** using a **Neural Network in PyTorch** to predict whether a tumor is **malignant or benign**.

The model is trained on the **Breast Cancer Wisconsin dataset** and achieves **~96% test accuracy**, demonstrating strong performance on a real-world medical dataset.

---

## 🚀 Key Features
- Built using **PyTorch (GPU supported)**
- End-to-end pipeline:
  - Data loading & preprocessing  
  - Feature scaling using `StandardScaler`  
  - Neural network training  
  - Model evaluation  
- Achieves **high accuracy (~96.49%) on test data**
- Clean and modular implementation

---

## 🗂️ Dataset
- Source: `sklearn.datasets.load_breast_cancer`
- Total samples: **569**
- Features: **30 numerical features**

### Target Classes:
- `0` → Malignant  
- `1` → Benign  

---

## ⚙️ Tech Stack
- Python 🐍  
- PyTorch 🔥  
- Scikit-learn  
- NumPy  

---

## 🧪 Model Architecture
A simple **Feedforward Neural Network**:








---

## 🛠️ Workflow

### 1. Data Preprocessing
- Train-test split (**80-20**)  
- Standardization using `StandardScaler`  
- Conversion to PyTorch tensors  
- GPU acceleration (if available)  

---

### 2. Training
- **Loss Function:** Binary Cross Entropy (`BCELoss`)  
- **Optimizer:** Adam  
- **Epochs:** 100  
- **Learning Rate:** 0.001  

---

### 3. Evaluation

| Dataset       | Accuracy |
|--------------|---------|
| Training Set | 97.36%  |
| Test Set     | 96.49%  |

---

## 📊 Results
- Model shows **strong generalization**
- Minimal **overfitting**
- Stable **training convergence**

---

## 💡 Future Improvements
- Add deeper neural networks  
- Apply Dropout for regularization  
- Perform hyperparameter tuning  
- Evaluate using ROC-AUC curve  
- Deploy using Flask / Streamlit  

---

## 🤝 Contributing
Feel free to fork this repository and contribute!

---

## 📬 Contact
**Prince Raj**  
📍 IIT Jodhpur  
🔗 GitHub: https://github.com/Spunkyiitj  
