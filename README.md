# Parkinson’s Disease Prediction using Machine Learning

## 📌 Overview
This project implements a **machine learning-based classification model** to predict the presence of Parkinson’s disease using biomedical voice measurements.  
It uses the **UCI Parkinson’s dataset** and applies data preprocessing, model training, evaluation, and visualization to assist in early detection of the disease.

---

## 📂 Dataset
- **Source:** [UCI Machine Learning Repository - Parkinson’s Dataset](https://archive.ics.uci.edu/ml/datasets/parkinsons)
- **Samples:** 195
- **Features:** 22 biomedical voice measures (MDVP frequency, jitter, shimmer, etc.)
- **Target:** Binary classification — 1 (Parkinson’s disease), 0 (Healthy)

---

## ⚙️ Methodology
1. **Data Loading & Exploration**
   - Read CSV dataset
   - Check data shape, types, and missing values
2. **Data Preprocessing**
   - Feature scaling using StandardScaler
   - Splitting into training and testing sets
3. **Model Building**
   - Train classification model (e.g., Logistic Regression, SVM, Random Forest)
4. **Model Evaluation**
   - Accuracy, Precision, Recall, F1-score
   - Confusion Matrix
5. **Visualization**
   - Correlation heatmap
   - Confusion matrix plot
   - Feature importance graph (for tree-based models)

---

## 📊 Results
- **Accuracy:** ~90% (varies by algorithm)
- **Key Observation:** Certain vocal features like MDVP:Fo(Hz) and jitter measures are strong predictors of Parkinson’s disease.

---

## 📌 Requirements
```bash
pip install numpy pandas matplotlib seaborn scikit-learn

git clone https://github.com/1shikapandey/Parkinson_Disease_Prediction_using_Machine_Learning_Python.git
cd Parkinson_Disease_Prediction_using_Machine_Learning_Python
python Parkinson_Disease_Prediction_using_Machine_Learning_Python.py
