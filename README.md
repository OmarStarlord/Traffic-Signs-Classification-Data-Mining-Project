# 🛑 Traffic Signs Classification — Data Mining Project

This project explores and compares several machine learning algorithms for **traffic sign image classification** using the Kaggle dataset **Traffic Signs Classification**.

📌 Dataset used:  
https://www.kaggle.com/datasets/flo2607/traffic-signs-classification/data

---

## 📁 Project Structure
---
├── classifieur_bayésien.ipynb
├── decision_trees.ipynb
├── knn.ipynb
├── neural_network.ipynb
├── svm.ipynb
└── README.md

## 📊 Dataset Description

The **Traffic Signs Classification** dataset contains labeled images of traffic signs belonging to multiple classes.  
It is designed for supervised multi-class image classification and is commonly used in computer vision and machine learning courses.

Main characteristics:
- RGB images of traffic signs
- Multiple traffic sign categories (classes)
- Suitable for classical ML and neural network approaches
- Provided via Kaggle

The dataset must be downloaded manually from Kaggle and placed in the project directory before running the notebooks.

---

## 🧪 Implemented Models

Each Jupyter notebook focuses on a specific classification method:

| Notebook | Algorithm |
|--------|----------|
| `classifieur_bayésien.ipynb` | Bayesian Classifier |
| `decision_trees.ipynb` | Decision Tree Classifier |
| `knn.ipynb` | K-Nearest Neighbors (KNN) |
| `neural_network.ipynb` | Neural Network |
| `svm.ipynb` | Support Vector Machine (SVM) |

All notebooks include:
- Data loading and preprocessing
- Model training
- Performance evaluation (accuracy, confusion matrix, etc.)

---

## ▶️ How to Run

1. Download the dataset from Kaggle:
   https://www.kaggle.com/datasets/flo2607/traffic-signs-classification/data
2. Extract the dataset into the project folder.
3. Open the notebooks using Jupyter:
   ```bash
   jupyter notebook


🛠 Requirements

Python 3.x

Jupyter Notebook

numpy

pandas

matplotlib

scikit-learn

tensorflow / keras (for neural network notebook)


📈 Objectives

Compare classical machine learning algorithms on image data

Evaluate strengths and limitations of each approach

Understand preprocessing and feature handling for image classification

Apply concepts from data mining and machine learning courses

📚 References

Kaggle – Traffic Signs Classification Dataset
https://www.kaggle.com/datasets/flo2607/traffic-signs-classification/data