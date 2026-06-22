❤️ Heart Disease Risk Prediction System

A Machine Learning-based Heart Disease Risk Prediction System that predicts the likelihood of heart disease using patient health parameters. The project compares multiple machine learning models, performs hyperparameter tuning, builds ensemble models, and provides risk analysis with automated email reporting.

📌 Project Overview

This project uses a heart disease dataset to:

Analyze patient health records
Perform feature engineering
Train multiple machine learning models
Compare model performance
Optimize models using hyperparameter tuning
Build ensemble models for improved accuracy
Predict heart disease risk for new patients
Generate health recommendations
Send prediction reports via email
🚀 Features
Data Preprocessing
Handles categorical and numerical data
One-hot encoding using Pandas
Feature scaling using StandardScaler
Train-Test split
Feature Engineering



Dataset :https://www.kaggle.com/datasets/arezaei81/heartcsv

Custom features created:

BP_HR_Ratio
Chol_Age
Exercise-related indicators
Machine Learning Models

The notebook trains and evaluates:

Logistic Regression
Random Forest
XGBoost
LightGBM
CatBoost
Neural Network (MLP Classifier)
Hyperparameter Tuning

Uses:

RandomizedSearchCV

For optimizing:

Random Forest
XGBoost
Ensemble Learning

Voting Classifier is used to combine multiple models:

XGBoost
Logistic Regression
Random Forest

This improves overall prediction performance.

Model Evaluation

Includes:

Accuracy Score
Confusion Matrix
Performance Comparison
Risk Prediction

For a new patient, the system provides:

Risk Percentage
Risk Status
Severity Level
Confidence Score
Health Recommendations
Email Reporting

Automatic email notifications containing:

Patient Information
Predicted Risk
Severity Analysis
Suggestions and Recommendations
🛠️ Technologies Used
Python
Pandas
NumPy
Scikit-Learn
XGBoost
LightGBM
CatBoost
Matplotlib
Seaborn
SMTP (Email Service)
Jupyter Notebook
📂 Project Structure
Heart Disease Prediction/
│
├── Max_2_min_Final.ipynb
├── heart.csv
├── README.md
│
└── Outputs
    ├── Model Accuracy
    ├── Confusion Matrix
    ├── Risk Prediction
    └── Email Report
📊 Workflow
Dataset
   ↓
Data Cleaning
   ↓
Feature Engineering
   ↓
Encoding & Scaling
   ↓
Train/Test Split
   ↓
Model Training
   ↓
Hyperparameter Tuning
   ↓
Ensemble Model
   ↓
Evaluation
   ↓
Risk Prediction
   ↓
Email Report
📈 Model Training Process
Load heart disease dataset.
Create additional health-related features.
Encode categorical variables.
Split dataset into training and testing sets.
Scale required features.
Train multiple ML models.
Compare accuracies.
Tune Random Forest and XGBoost.
Build Voting Ensemble.
Predict heart disease risk.
🩺 Example Prediction Output
Patient Name: P. Narayana
Age: 45

Risk Percentage: 78%
Status: High Risk

Severity: Moderate to High

Recommendations:
✔ Consult a Cardiologist
✔ Maintain Healthy Diet
✔ Regular Exercise
✔ Monitor Blood Pressure
✔ Reduce Cholesterol Levels
⚙️ Installation
Clone Repository
git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction
Install Dependencies
pip install pandas numpy scikit-learn
pip install xgboost lightgbm catboost
pip install matplotlib seaborn
Run Notebook
jupyter notebook

Open:

Max_2_min_Final.ipynb
📋 Dataset

The project uses a Heart Disease Dataset containing features such as:

Age
Sex
Chest Pain Type
Resting Blood Pressure
Cholesterol
Fasting Blood Sugar
Resting ECG
Max Heart Rate
Exercise Angina
Oldpeak
ST Slope

Target:

HeartDisease
0 → No Heart Disease
1 → Heart Disease
🎯 Future Improvements
Web Application Deployment
Real-Time Prediction API
PDF Report Generation
Doctor Dashboard
Patient History Tracking
Explainable AI (SHAP/LIME)
👨‍💻 Author

Sanjay Gandhi

Machine Learning Project for Heart Disease Risk Prediction using Ensemble Learning and Advanced Classification Models.

📜 License

This project is intended for educational and research purposes only. It should not be used as a replacement for professional medical diagnosis.
