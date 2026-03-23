# PulseNet

A machine learning project for heart disease prediction using EDA, data preprocessing, and feature engineering. Implements multiple models including Logistic Regression, KNN, SVM, Naive Bayes, and Decision Tree, with performance evaluation. The best model is saved for deployment.

---

## 🚀 Project Overview

This project uses a trained **K-Nearest Neighbors (KNN)** model to predict whether a person is at **high risk or low risk of heart disease** based on medical attributes such as age, cholesterol, blood pressure, etc.

The application provides a simple UI where users can input their health details and instantly get predictions.

---

## 🧠 Machine Learning Workflow

* Data Collection (`heart.csv`)
* Data Preprocessing & Feature Engineering
* Feature Scaling using StandardScaler
* Model Training using KNN
* Model Saving using Joblib
* Deployment using Streamlit

---

## 📁 Project Structure

```
Heart-Disease-Prediction/
│
├── app.py                      # Streamlit web application
├── heart.csv                   # Dataset used for training
├── HeartdiseaseFinal.ipynb     # Jupyter notebook (training & analysis)
│
├── models/                     # Folder for all saved model files
│   ├── knn_heart_model.pkl
│   ├── heart_scaler.pkl
│   └── heart_columns.pkl
│
├── requirements.txt            # Project dependencies
└── README.md                   # Project documentation
```

---

## ⚙️ Features

* Interactive web interface using Streamlit
* Real-time prediction
* Data preprocessing handled automatically
* User-friendly sliders and dropdown inputs
* Accurate predictions using trained ML model

---

## 🖥️ How to Run the Project

### 1. Clone the Repository

```
git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction
```

### 2. Install Dependencies

```
pip install -r requirements.txt
```

### 3. Run the Application

```
streamlit run app.py
```

---

## 📊 Input Features

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG
* Maximum Heart Rate
* Exercise-Induced Angina
* Oldpeak
* ST Slope

---

## 🎯 Output

* ✅ Low Risk of Heart Disease
* ⚠️ High Risk of Heart Disease

---

## 🛠️ Tech Stack

* Python
* Pandas
* Scikit-learn
* Joblib
* Streamlit

---

## 📌 Future Improvements

* Add more advanced models (Random Forest, XGBoost)
* Improve UI/UX design
* Deploy on cloud (Streamlit Cloud / AWS / Heroku)
* Add user authentication & history tracking

---

## 🙌 Author

**Priyanshu Das**

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!

---
