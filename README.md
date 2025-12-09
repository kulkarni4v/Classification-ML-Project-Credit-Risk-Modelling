<!-- PROJECT TITLE -->
<h1 align="center">💳 Credit Risk Prediction – Machine Learning Model Deployment</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Deployment-Streamlit%20Cloud-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Model-Classification-orange?style=for-the-badge" />
</p>

---

## 🚀 **Live Demo**

<p align="center">
  <a href="https://classification-ml-project-credit-risk-modelling-tkmyawc8stj3mu.streamlit.app/">
    <img src="https://img.shields.io/badge/🌐%20Open%20Streamlit%20App-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
  </a>
</p>

👉 **Click the button above** to try the real-time **interactive Credit Risk Prediction App** deployed on **Streamlit Cloud**.

---

## 🔥 **Project Overview**

This project provides a complete pipeline for building and deploying a **Credit Risk Prediction Model** using Machine Learning.  
It includes:

- 🧠 **Model training notebook**
- 📦 **Streamlit app for deployment**
- 🔍 **Prediction pipeline**
- 📊 **Datasets for training & analysis**
- ☁️ **Fully deployed live version**

---

## 🛠️ **Tech Stack & Libraries**

### **Languages**
<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="60" />
</p>

### **Frameworks & Tools**
<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/streamlit/streamlit-original.svg" width="55" />
</p>

### **Libraries Used**
<p align="left">
  <img src="https://pandas.pydata.org/static/img/pandas_secondary.svg" width="95" />
  <img src="https://numpy.org/images/logo.svg" width="85" />
  <img src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width="90" />

</p>

---

## 📁 **Project Structure**

```text
Project2_Deployment_Resources/
│
├── credit_risk_model_codebasics.ipynb     # Notebook for training the ML model
│
├── app/                                   # Deployment-ready application
│   ├── main.py                             # Streamlit app (frontend + inference)
│   ├── prediction_helper.py                # Preprocessing + model prediction logic
│   └── artifacts/
│       └── model_data.joblib               # Trained ML model
│
├── artifacts/
│   └── model_data.joblib                   # Backup model artifact
│
└── dataset/
    ├── bureau_data.csv
    ├── customers.csv
    └── loans.csv
