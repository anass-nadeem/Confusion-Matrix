# 🍷 Wine Classifier — ML Model Evaluation with Confusion Matrix

A machine learning project that trains a multi-class classifier on the 
Wine dataset and evaluates model performance using a confusion matrix, 
classification report, and prediction analysis.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikit-learn)
![Jupyter](https://img.shields.io/badge/Notebook-Colab-yellow?logo=googlecolab)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Overview

This project demonstrates a complete ML classification pipeline — from 
data loading and preprocessing to model training, prediction, and 
performance evaluation. The confusion matrix is used to break down 
per-class accuracy and identify where the model succeeds and where it 
misclassifies.

---

## 🧠 What This Project Covers

- Multi-class classification using Scikit-Learn
- Confusion matrix construction and heatmap visualization
- Precision, recall, and F1-score interpretation
- Exporting predictions to CSV for further analysis

---

## 📊 Dataset

- **Source:** `sklearn.datasets` — Wine Dataset
- **Classes:** WineA, WineB, WineC (3-class classification)
- **Features:** 13 chemical properties (alcohol, malic acid, flavonoids, etc.)

---

## 📁 Project Structure

├── Confusion Matrix.ipynb       # Full ML pipeline notebook
├── wine_unique_predictions.csv  # Actual vs Predicted output
└── README.md

---

## ▶️ How to Run

1. Open `Confusion Matrix.ipynb` in [Google Colab](https://colab.research.google.com/)
2. Run all cells sequentially
3. Output includes:
   - ✅ Confusion matrix heatmap
   - ✅ Full classification report (precision, recall, F1)
   - ✅ CSV of actual vs predicted labels

---

## 📈 Key Results

| Metric | Score |
|--------|-------|
| Model | Decision Tree / SVM (Scikit-Learn) |
| Classes | WineA, WineB, WineC |
| Evaluation | Confusion Matrix + Classification Report |

---

## 👤 Author

**Muhammad Anas Nadeem**  
BSAI Student @ CUST Islamabad  
[LinkedIn](https://www.linkedin.com/in/muhammadanas-nadeem-970300354) · 
[GitHub](https://github.com/anass-nadeem)

---

## 📜 License

MIT
