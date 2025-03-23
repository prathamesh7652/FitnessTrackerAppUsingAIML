Fitness Tracker App - AI/ML Powered

📌 Overview

The Fitness Tracker App is an intelligent fitness monitoring application that leverages AI/ML techniques to analyze user activity, predict health metrics, and provide personalized fitness recommendations. The app integrates the Random Regressor Model to estimate various fitness-related parameters, ensuring accurate and data-driven insights.

🚀 Features

Activity Tracking: Monitor calories burned and exercise routines.

AI-Powered Predictions: Utilize machine learning models to predict calorie expenditure based on exercise type and intensity.

Data Visualization: Interactive charts and graphs to analyze fitness progress.

Real-Time Insights: Continuous monitoring and updates based on user activity trends.

🛠️ Technology Stack

Frontend: Streamlit (for a visually appealing and interactive UI)

Backend: Python (for data processing and ML model execution)

Machine Learning Model: Random Regressor (for predicting calorie expenditure)

Dataset: CSV files (calories.csv and exercise.csv) for data storage

🔬 AI/ML Implementation

The core of this fitness tracker app is the Random Regressor Model, a machine learning algorithm that predicts calorie expenditure based on different types of exercises. The workflow includes:

Data Collection: Using CSV datasets (calories.csv and exercise.csv) to store fitness-related data.

Preprocessing: Cleaning and normalizing data for accurate analysis.

Model Training: Using a Random Regressor to learn from historical fitness data.

Prediction & Insights: Generating real-time fitness insights based on user input.

📥 Installation & Setup

Clone the repository:

git clone https://github.com/prathamesh7652/FitnessTrackerAppUsingAIML

Navigate to the project folder:

cd FitnessTrackerAppUsingAIML

Install dependencies:

pip install -r requirements.txt  # Install required Python packages

Run the application:

streamlit run app.py  # Start the Streamlit frontend

📌 Usage Guide

Load Dataset: The app uses calories.csv and exercise.csv as input data sources.

Enter Exercise Details: Provide exercise type, duration, and intensity.

Get Predictions: AI model predicts calorie expenditure based on input.

View Insights: Interactive graphs and real-time analysis of fitness trends.


Project live on --
https://aibasedfitnessapp.streamlit.app/




