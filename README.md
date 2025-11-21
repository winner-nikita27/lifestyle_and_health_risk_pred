About this Dataset
📘 Description:
This synthetic health dataset simulates real-world lifestyle and wellness data for individuals.
It is designed to help data scientists, machine learning engineers, and students build and test health risk prediction models safely — without using sensitive medical data.

The dataset includes features such as age, weight, height, exercise habits, sleep hours, sugar intake, smoking, alcohol consumption, marital status, and profession, along with a synthetic health_risk label generated using a heuristic rule-based algorithm that mimics realistic risk behavior patterns.

🧩 Use Cases:
Health Risk Prediction:
Train classification models (Logistic Regression, RandomForest, XGBoost, CatBoost) to predict health risk (low / high).
Feature Importance Analysis:
Identify which lifestyle factors most influence health risk.
Data Preprocessing & EDA Practice:
Use this dataset for data cleaning, encoding, and visualization practice.
Model Explainability Projects:
Use SHAP or LIME to explain how different lifestyle habits affect predictions.
Streamlit or Flask Web App Development:
Build a real-time web app that predicts health risk from user input.
💡 Case Study Example:
Imagine you are a data scientist building a Health Risk Prediction App for a wellness startup.
You want to analyze how exercise, sleep, and sugar intake affect overall health risk.
This dataset helps you simulate those relationships without handling sensitive medical data.
You could:

Perform EDA to find correlations between age, BMI, and health risk.
Train a model using Random Forest to predict health_risk.
* Deploy a Streamlit app where users can input their lifestyle information and get a risk score instantly.
* 
⚙️ Technical Information:
Rows: 5,000 (adjustable, you can create more)
Columns: 12
Target variable: health_risk
Data type: Mixed (Numeric + Categorical)
* Source: Fully synthetic, generated using Python (NumPy, Faker)
* 
📈 License:
CC0: Public Domain

You are free to use this dataset for research, learning, or commercial projects.
🌍 Author:
Created by Arif Miah
Machine Learning Engineer | Kaggle Expert | Data Scientist
