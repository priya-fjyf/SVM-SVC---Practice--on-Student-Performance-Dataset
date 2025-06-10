# SVM-SVC---Practice--on-Student-Performance-Dataset
This repository contains a practical implementation of Support Vector Machine (SVM) classification using the SVC (Support Vector Classifier) from Scikit-learn, applied to a real-world dataset on student performance. The goal is to predict student performance categories (such as pass/fail or grade groups) based on features like study time, etc.
## This project demonstrates the use of **Support Vector Machine (SVC)** on a real-world **student performance dataset**, with and without **PCA (Principal Component Analysis)** to improve classification.
## 📊 Dataset

T### he dataset includes features like:
1.- Study time
2.- Parental education
3.- Internet access
4.- Gender, etc.

# 🎯 **Goal**: Predict student performance (Excellent/Average/Good or category).
## ⚙️ Workflow

1. Data preprocessing & EDA  
2. Training SVC models (`rbf` kernels)  
3. Accuracy evaluation  
4. PCA application for dimensionality reduction  
5. Visual analysis & comparison

---

## 📈 Results

| Model          | Accuracy 🎯 |
|----------------|-------------|
| Without PCA    | ✅ 91%      |
| With PCA       | 🚀 92%      |

📌 PCA slightly improved accuracy and reduced dimensionality.

---

## 🧰 Tools Used

- Python, Pandas, NumPy  
- Scikit-learn (`SVC`, `PCA`, metrics)  
- Matplotlib, Seaborn

---

## 📁 Files

- `svm_student_performance.ipynb` → Main notebook  
- `student_performance.csv` → Dataset  
- `plots/` → Visuals (decision boundaries, PCA, confusion matrix)



