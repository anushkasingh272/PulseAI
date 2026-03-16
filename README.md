Project Overview

This project aims to predict whether a person is at risk of heart disease using various medical attributes such as age, cholesterol level, blood pressure, and other health indicators. Early detection of heart disease can help healthcare professionals and individuals take preventive measures and enable timely medical intervention.

Dataset

The dataset contains medical information of patients used to train the machine learning model. Important features include:

Age – Age of the patient

Sex – Gender of the patient

Chest Pain Type – Type of chest pain experienced

Resting Blood Pressure – Blood pressure measured at rest

Cholesterol – Serum cholesterol level

Maximum Heart Rate – Maximum heart rate achieved during exercise

Fasting Blood Sugar – Indicates whether fasting blood sugar is above normal level

Exercise Induced Angina – Presence of chest pain during exercise

These attributes help the model learn patterns associated with heart disease risk.

Technologies Used

The project is implemented using the following technologies:

Python – Programming language used for development

Pandas & NumPy – Data manipulation and numerical computation

Scikit-learn – Machine learning model development and evaluation

Streamlit – Building an interactive web application for prediction

Matplotlib & Seaborn – Data visualization and exploratory data analysis (EDA)

Workflow

The machine learning pipeline follows these steps:

Data Loading and Cleaning – Importing the dataset and handling missing or inconsistent values.

Encoding Categorical Variables – Converting categorical features into numerical format.

Feature Scaling (Optional) – Normalizing numerical features for better model performance.

Train-Test Split – Splitting the dataset into training and testing sets.

Model Training – Training a Logistic Regression model on the dataset.

Model Evaluation – Evaluating performance using metrics such as Accuracy, Precision, Recall, F1 Score, and Confusion Matrix.

Web Application Development – Creating a Streamlit-based web interface where users can input health parameters and receive predictions.

Features

User-friendly web interface for entering patient health data

Machine learning prediction for heart disease risk (High / Low)

Displays prediction confidence

Interactive Streamlit web application

Future Improvements

Implement advanced models such as Random Forest, Gradient Boosting, or XGBoost

Perform hyperparameter tuning to improve model accuracy

Deploy the application on the cloud with user authentication and secure access
