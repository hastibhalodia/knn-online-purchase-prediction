# 🛒 Predicting Online Purchase Intent Using KNN

This project focuses on predicting whether an online user will complete a purchase based on their session behavior. We use the **K-Nearest Neighbors (KNN)** algorithm along with various data preprocessing, dimensionality reduction (PCA), class balancing (SMOTE), and model comparison techniques to develop an accurate and insightful customer behavior model.

---

## 📂 Dataset

The dataset used in this project is the **Online Shoppers Purchasing Intention** dataset.

🔗 **Download here**: [Google Drive Dataset Link](https://drive.google.com/file/d/1phEyFJa1492KyRWJWJNw9FsoBR1WuTUx/view?usp=sharing)

It contains information about:
- Session durations
- Page types visited
- Bounce rates
- Traffic types
- Visitor types
- Whether the session ended with a purchase

---

## ✅ Project Goals

- Predict online purchase intent using KNN
- Handle class imbalance with SMOTE
- Reduce dimensionality using PCA
- Compare multiple machine learning models (Logistic Regression, Decision Tree, Random Forest)
- Demonstrate bias-variance tradeoff and the curse of dimensionality
- Extract business insights from model predictions

---

## 📌 Key Steps

1. **Import libraries and load dataset**
2. **Preprocess data**: Encode categorical values, handle boolean features
3. **Feature scaling** using `StandardScaler`
4. **Train/test split** using stratified sampling
5. **Baseline KNN model** with performance evaluation
6. **Bias-Variance Tradeoff**: Tune `k` and analyze overfitting/underfitting
7. **Curse of Dimensionality**: Add noise features and observe performance drop
8. **PCA** for dimensionality reduction
9. **Compare models**: Logistic Regression, Decision Tree, Random Forest
10. **Handle class imbalance** with SMOTE
11. **Summarize results and extract business insights**

---

## 📊 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix
- ROC Curves

---

## 🧠 Insights

- KNN works well with proper feature scaling but struggles with high-dimensional noisy data.
- Random Forest generally outperforms other models in both accuracy and generalization.
- SMOTE improves minority class recall and F1-score.
- PCA effectively reduces feature space and improves KNN efficiency.

---

## 🛠️ Technologies Used

- Python 3
- NumPy, Pandas
- Scikit-learn
- Matplotlib, Seaborn
- imbalanced-learn (for SMOTE)

---

## 📎 License

This project is for academic and research purposes under guidance from **Samatrix Consulting Pvt Ltd**. Do not distribute without permission.

---
