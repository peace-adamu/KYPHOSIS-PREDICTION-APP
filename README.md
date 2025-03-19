# Project Title: Kyphosis Detection System
- [Project Preview](#project-preview)
- [Project Objective](#project-objective)
- [Project Significant](#project-significant)
- [Features](#features)
- [Project Methodology](#project-methodology)
- [Prerequisites](#prerequisites)
- [Web Application Usage](#web-application-usage)
- [Disccussion of Result](#discussion-of-result)
- [Deploment](#deployment)


## Project Preview
This project contains a web-based Kyphosis Detection System utilizing machine learning algorithms and Streamlit. The system predicts whether a patient has kyphosis based on their medical characteristics.

## Project Objective
The main objective of this project is to develop a machine learning-based web application that predicts kyphosis based on spinal characteristics. The application provides a user-friendly interface where users can input their details and receive an instant prediction of their kyphosis status.

## Project Significance
- Provides quick and reliable kyphosis prediction.
- Enhances accessibility for users without technical expertise.
- Uses machine learning to improve prediction accuracy.
- Aids in early detection and intervention for kyphosis management.

## Features 
The following features are used for prediction:
- Age: Age of the patient in months.
- Number: Number of vertebrae involved in the curvature.
- Start: The starting vertebra of the curvature.

## Project Methodology
- Data Collection – Dataset containing kyphosis patient records.
- Data Preprocessing – Cleaning, normalization, and feature selection.
- Model Training – Machine learning model trained on labeled data.
- Model Evaluation – Performance assessed using precision, recall, F1-score, and confusion matrix.
- Web Application Deployment – Model integrated into a Streamlit web app for easy accessibility.

  ## Prerequisites
To run this project locally, you need:
- Python 3.13.0
- Streamlit 1.42.2
- Scikit-learn 1.6.1
- Joblib 1.4.2

  ## Web Application Usage
- Install required packages:
- pip install streamlit scikit-learn joblib
- Run the app:
streamlit run app.py
- Input patient data and click the Predict button to get the prediction result.


## Discussion of Result
The performance of the kyphosis detection model was evaluated using a classification report and confusion matrix.

''Classification Report

              precision    recall  f1-score   support

           0       1.00      1.00      1.00        11
           1       1.00      1.00      1.00         6

    accuracy                           1.00        17
   macro avg       1.00      1.00      1.00        17
weighted avg       1.00      1.00      1.00        17

Confusion Matrix

[[11  0]
 [ 0  6]]''

- The model achieved high accuracy, demonstrating strong predictive capability.
- The model shows exceptional performance with an accuracy of 100% on the test set. The classification report and confusion matrix confirm that the model effectively distinguishes between kyphosis presence and absence.
- This system is an important step towards leveraging AI in healthcare for early kyphosis detection, which can lead to timely medical interventions and better health outcomes for individuals.

## Deployment
This app is been deployed with streamlit, you can access it:https://kyphosis-prediction-app-pwgrqpzbyzcmhyi3ah2w6d.streamlit.app/
