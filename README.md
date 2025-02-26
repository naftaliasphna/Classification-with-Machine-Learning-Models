# 🩺 Breast Cancer Classification with Machine Learning Models  

## 📌 Project Overview
This project aims to build a machine learning model to classify breast tumors as benign or malignant using the scikit-learn dataset. The tested models include SVM, Logistic Regression, Random Forest, KNN, and Naïve Bayes, compared to determine the best performance in breast cancer classification.

## 🎯 Goal
The primary objective of this project is to develop an accurate and efficient machine learning model for breast cancer classification.

## 🔬 Dataset  
The dataset used in this project is the **Breast Cancer  Wisconsin Dataset** sourced from Scikit-Learn.

- **Target Variable:**  
  - `Malignant (1)`  =  Non-cancerous tumor
  - `Benign (0)`  =  Cancerous tumor

- **Features Include:**  
  - Mean, standard error, and worst-case values for attributes such as **radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, and fractal dimension**  

## 📊 Machine Learning Models Used  
The following machine learning models are implemented and evaluated in this project:  

- **Support Vector Machine (SVM)**
- **Logistic Regression**  
- **Random Forest**
- **K-Nearest Neighbour**
- **Naive Bayes**      

## 🚀 Features & Workflow  
- Data Preprocessing (Handling missing values, feature scaling)
- Exploratory Data Analysis (EDA) with visualizations
- Model Training & Evaluation
- Performance Comparison of Different ML Models
- Insights & Conclusion  

## 📌 Results & Best Model Analysis  
- All five models (SVM, Logistic Regression, Random Forest, KNN, and Naive Bayes) performed well in terms of classification accuracy.
The **Support Vectoer Machine** model showed the highest accuracy among all models, which is **98.25%**. Logistic Regression achieved an accuracy of 97.37%; Random Forest achieved an accuracy 94.74%; KNN achieved an accuracy of 95.61%; and Naive Bayes achieved an accuracy of 96.49%.   
- The **confusion matrix** showed that SVM correctly classified **41 malignant and 71 benign cases**, with only **2 false negatives and no false positives**.  
- Training accuracy: **98.68%**, Testing accuracy: **97.37%**, indicating **no overfitting or underfitting** on SVM model.  

## 🛠️ Technologies Used  
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
