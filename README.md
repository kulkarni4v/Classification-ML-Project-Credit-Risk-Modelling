# Classification-ML-Project-Credit-Risk-Modelling
Logistic Regression making predictions whether the given customer could be a defaulter or not , based on customer's financial attributes and requirements

---

This project provides a complete setup for deploying a Credit Risk Prediction machine-learning model. It includes the trained model artifacts, dataset samples, and a lightweight API Streamlit built with Python for serving predictions.
----------------------------------------------------------------------------------------------------
Project Strucutre

Project2_Deployment_Resources/
│
├── credit_risk_model_jupyter_notebook.ipynb     # Notebook used for model training & experimentation
│
├── app/                                   # Deployment-ready application
│   ├── main.py                             # Main API / Streamlit app
│   ├── prediction_helper.py                # Feature processing & model invocation utilities
│   └── artifacts/
│       └── model_data.joblib               # Serialized trained ML model for predictions
│
├── artifacts/
│   └── model_data.joblib                   # Standalone copy of the trained model
│
└── dataset/                                # Sample dataset used in model development
    ├── bureau_data.csv
    ├── customers.csv
    └── loans.csv
-----------------------------------------------------------------------------------------------------

🚀 Overview

This project is designed to:

Train a credit-risk machine-learning model using historical customer, loan, and bureau data.

Package the trained model using joblib.

Expose the model through a simple API for online inference.

Provide datasets and notebooks for further experimentation or retraining.

The API accepts customer & loan input features and returns the predicted probability of loan default.

🧠 Model Training

Model training is performed in:

credit_risk_model_jupyter_notebook.ipynb


This notebook includes:

Data preprocessing

Feature engineering

Model training (likely RandomForest / XGBoost / Logistic Regression depending on code)

Model evaluation (ROC-AUC, accuracy, etc.)

Exporting the model to model_data.joblib

🏗️ API Application

API logic is located inside:

app/
    main.py
    prediction_helper.py

main.py

Handles HTTP routes for prediction.

Loads the ML model from artifacts/model_data.joblib.

Defines request/response schemas.

Calls helper functions to preprocess inputs and run inference.

prediction_helper.py

Contains:

Feature-processing utilities

Model loading & prediction functions

Any transformations required to align inputs with what the model expects


Credits: Codebasics
