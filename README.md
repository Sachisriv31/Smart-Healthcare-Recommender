# Smart-Healthcare-Recommender
🩺 Smart-Healthcare-Recommender
Disease Prediction and Medical Recommendation System

A machine learning-powered web application that predicts diseases based on user-entered symptoms and provides comprehensive health recommendations — including medications, diet, workouts, and preventive care.

🎯 Features

🧠 Intelligent Disease Prediction
Predicts the most probable disease using a Random Forest Classifier with near-perfect accuracy.

✍️ Symptom Spell Correction
Employs fuzzy matching to correct misspelled or incomplete symptoms automatically.

💊 Personalized Medical Recommendations

Detailed disease descriptions

Medication and treatment suggestions

Dietary and nutritional advice

Exercise and fitness plans

Preventive precautions

🌐 Interactive Web Interface
Simple, responsive design built with Flask and Bootstrap 5 for a seamless user experience.

⚡ Real-Time Results
Instant predictions and recommendations based on user input.

🚀 Technologies Used

Python, Flask, scikit-learn, pandas, numpy, HTML, CSS, Bootstrap, pickle

📊 Dataset Information

The model is trained on a comprehensive medical dataset containing:

41 diseases

132 symptoms

Curated recommendations for each disease

Dataset includes:
Training.csv, symptoms_df.csv, description.csv, medications.csv, diets.csv, workout_df.csv, precautions_df.csv, and symptom-severity.csv

🧠 Model Overview

Algorithm: Random Forest Classifier

Accuracy: ~100% on training data

Goal: Predict disease from symptoms and generate relevant health guidance

💬 Summary

Smart-Healthcare-Recommender acts as your AI-powered medical assistant, helping users identify potential diseases from symptoms and receive instant, personalized health advice — all through an easy-to-use web interface.
