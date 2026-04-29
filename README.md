# Credit-Card-Fraud-Detection-Using-Machine-Learning
Credit Card Fraud Detection System  A Machine Learning-based web application that detects fraudulent credit card transactions in real time using transaction details and behavioral patterns. The system is built using LightGBM, SMOTE, and Streamlit, providing an efficient and user-friendly fraud detection solution.

Features:
Real-time fraud prediction
Interactive Streamlit web interface
Machine Learning model trained using LightGBM
Handles imbalanced datasets using SMOTE
Geographical distance calculation using Geopy
Encodes categorical data using Label Encoders
Model persistence using Joblib
Detects suspicious transaction behavior based on:
Merchant details
Transaction amount
Location distance
Time-based features
User information

Technologies Used:
Python
Streamlit
Pandas
LightGBM
Scikit-learn
Joblib
Geopy
SMOTE (Synthetic Minority Oversampling Technique)

Model Information:

The fraud detection model is trained using LightGBM, which is highly efficient for large datasets and classification problems.

Additional preprocessing includes:

Label Encoding for categorical variables
Hashing for credit card numbers
SMOTE for balancing fraud and non-fraud classes
