# Cardiac Arrest Prediction using Machine Learning and Model Deployment using Flask API

**Introduction:**

Predicting cardiac arrest is a critical component of proactive healthcare, potentially saving lives by enabling timely medical interventions. By leveraging machine learning algorithms to analyze patient data, it is possible to identify individuals at high risk of cardiac arrest, facilitating early intervention and improved patient outcomes. This project aims to develop a predictive model for cardiac arrest using machine learning and deploy the model using a Flask API for real-time risk assessment and decision support.

**Problem Statement:**

The objective of this project is to develop a machine learning model that predicts the likelihood of cardiac arrest based on patient health data. The project involves training the model on historical medical data to identify risk factors and patterns associated with cardiac arrest. Once developed, the model will be deployed using a Flask API, providing a user-friendly interface for real-time predictions. The goal is to create a reliable prediction system that assists healthcare professionals in identifying high-risk patients and improving preventive care strategies.

**Dataset:**

The dataset used for this project has 70,000 records and has the following columns:

(i)   Gender - Gender of the person	

(ii)  Height	- Height of the person

(iii) Weight	- Weight of the person

(iv)  Smoke- Whether the person smokes or not (Y/N)

(v)   Alcohol - Whether the person consumes alcohol (Y?N)	

(vi) Cardio - Whether the person will get cardiac arrest or not

**Project Description:**

• Performed Data Pre-Processing to prepare data for model building.

• Developed a Random Forest Model to predict Cardiac Arrest.

• Leveraged the Pickle Library to save the model 

• Created a user-friendly HTML form for inputting health metrics, including gender, height, weight, smoking, and alcohol consumption.

• Implemented a Flask API to handle form submissions and return real-time predictions for cardiac arrest risk using a pre-trained model.

• Ensured dynamic feedback to users by displaying the probability of cardiac arrest based on their inputs directly on the web page.

**Skills:** Model Deployment · Data Pre-Processing · Random Forest · Pickle Library · HTML · Flask API
