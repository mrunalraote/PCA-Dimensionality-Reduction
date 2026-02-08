# Task 13: PCA – Dimensionality Reduction

## 📌 Objective
The objective of this task is to apply **Principal Component Analysis (PCA)** to reduce the dimensionality of image data while preserving maximum variance and to analyze the impact of dimensionality reduction on model performance.

---

## 📊 Dataset
- **Primary Dataset:** Sklearn Digits Dataset  
- The dataset contains 8×8 grayscale images of handwritten digits (0–9).
- Each image is flattened into **64 features**.

---

## 🛠 Tools & Technologies
- Python  
- Scikit-learn  
- Matplotlib  
- Google Colab   

---

## 🔍 Methodology
1. Loaded the digits dataset from Scikit-learn.
2. Flattened image data into feature vectors.
3. Scaled features using **StandardScaler** for proper PCA performance.
4. Applied **PCA** with multiple component values (2, 10, 30, 50).
5. Plotted **cumulative explained variance** to analyze variance retention.
6. Reduced the dataset dimensionality using optimal PCA components.
7. Trained **Logistic Regression** on:
   - Original dataset  
   - PCA-reduced dataset
8. Compared accuracy before and after dimensionality reduction.
9. Visualized the dataset using **2D PCA scatter plot**.

---

## 📈 Deliverables

### 1️⃣ Explained Variance Plot
- A cumulative explained variance plot was generated to identify how many PCA components preserve most of the variance.

### 2️⃣ Reduced Dataset
- The original dataset (64 features) was reduced to **30 principal components** using PCA.
- This significantly reduced dimensionality while retaining most information.

### 3️⃣ Accuracy Comparison Report

| Model | Accuracy |
|------|----------|
| Original Dataset | High accuracy |
| PCA Reduced Dataset | Slightly reduced accuracy |

- The results show a **trade-off between dimensionality reduction and accuracy**.

- ##Author
- Mrunal Vijay Arote

---

## 📁 Project Structure
