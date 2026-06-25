# 🩺 Breast Cancer Prediction Using K-Nearest Neighbors (KNN)

## 📌 Project Overview

This project implements a **K-Nearest Neighbors (KNN)** machine learning model to classify breast tumors as **Malignant (Cancerous)** or **Benign (Non-Cancerous)** using the Breast Cancer Wisconsin Diagnostic Dataset.

The project demonstrates a complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature scaling, model training, hyperparameter tuning, model evaluation, and prediction.

---

## 🎯 Objective

The objective of this project is to build a classification model that accurately predicts whether a breast tumor is malignant or benign based on 30 diagnostic features extracted from digitized images of fine needle aspirate (FNA) of breast masses.

---

## 📂 Dataset Information

- **Dataset:** Breast Cancer Wisconsin Diagnostic Dataset
- **Total Records:** 569
- **Features:** 30 Numerical Features
- **Target Variable:** `diagnosis`
  - **M** → Malignant
  - **B** → Benign

### Feature Examples

- Radius Mean
- Texture Mean
- Perimeter Mean
- Area Mean
- Smoothness Mean
- Compactness Mean
- Concavity Mean
- Symmetry Mean
- Fractal Dimension Mean
- And other derived measurements

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Exploratory Data Analysis (EDA)

The following visualizations were performed to better understand the dataset:

- Dataset Overview
- Missing Value Analysis
- Class Distribution
- Correlation Heatmap
- Histogram of Features
- Boxplots for Outlier Detection
- Scatter Plots
- Pair Plot
- Feature Distribution Analysis

---

## ⚙️ Data Preprocessing

- Removed unnecessary columns (`id`)
- Encoded the target variable (`diagnosis`)
- Checked for missing values
- Split the dataset into training and testing sets
- Standardized numerical features using **StandardScaler**

---

## 🤖 Machine Learning Model

### Algorithm Used

**K-Nearest Neighbors (KNN)**

KNN is a supervised machine learning algorithm that classifies new data points by identifying the **K nearest neighbors** based on distance and assigning the majority class.

---

## 🔧 Model Training

- Train-Test Split
- Feature Scaling
- Model Training
- Hyperparameter Tuning (Finding the Best K Value)

---

## 📈 Model Evaluation

The model was evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
- Accuracy vs K Graph

---

## 📉 Visualizations

- Diagnosis Distribution
- Missing Values Heatmap
- Correlation Heatmap
- Histogram
- Boxplot
- Scatter Plot
- Pair Plot
- Confusion Matrix
- Accuracy vs K Curve

---

## 🚀 Workflow

1. Import libraries
2. Load the dataset
3. Perform Exploratory Data Analysis (EDA)
4. Preprocess the data
5. Encode categorical values
6. Scale numerical features
7. Split data into training and testing sets
8. Train the KNN classifier
9. Tune the value of K
10. Evaluate model performance
11. Predict diagnosis for new patient data
12. 
---

## 📚 Key Learning Outcomes

- Understood the working of the K-Nearest Neighbors (KNN) algorithm.
- Learned why feature scaling is essential for distance-based algorithms.
- Performed Exploratory Data Analysis (EDA) using data visualization techniques.
- Applied data preprocessing techniques including encoding and scaling.
- Evaluated model performance using multiple classification metrics.
- Tuned hyperparameters to improve prediction accuracy.
- Built an end-to-end machine learning classification project.

---

## 🔮 Future Improvements

- Compare KNN with Logistic Regression, Decision Tree, Random Forest, and SVM.
- Perform feature selection to reduce dimensionality.
- Optimize the model using GridSearchCV.
- Build a web application using Streamlit or Flask for real-time predictions.
- Deploy the trained model to the cloud.

---

## 📌 Conclusion

This project demonstrates how the **K-Nearest Neighbors (KNN)** algorithm can effectively classify breast tumors using medical diagnostic features. Through data preprocessing, feature scaling, model training, and evaluation, the project highlights the importance of machine learning in supporting early breast cancer detection and assisting healthcare professionals in making data-driven decisions.

---

## 👨‍💻 Author

**M. Rajesh Nayak**

Machine Learning Enthusiast | Python Developer | Data Science Learner

---
