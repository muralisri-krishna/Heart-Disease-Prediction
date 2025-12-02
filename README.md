# Heart-Disease-Prediction
📌 Project Summary

This system predicts heart disease risk in patients using medical features and a trained machine learning model. It is built as a full-stack web application using Django (Python framework). The model analyzes health parameter inputs and predicts whether the patient has a high probability of heart disease.

➡️ The project supports user registration, login, heart disease prediction input forms, and result visualization.

🎯 Project Goal

✔ Assist doctors and patients with early heart disease risk screening
✔ Enable easy & digital access to prediction system via web browser
✔ Reduce medical diagnosis time using AI
✔ Secure user data with credentials and session management

🧠 System Architecture & Workflow

📌 Core Modules (as per SCREENSHOTS.docx) 

SCREENSHOTS

Module	Purpose
User Registration	New users register into the system
User Login	Authentication and session validation
Prediction Feature	Inputs patient heart-related features
ML Model Interface	Predicts risk based on trained classifier
Result Display	Shows whether disease is likely or not
🧪 Machine Learning Approach
🔹 Algorithm Used: Naïve Bayes

Works best for medical classification

Handles categorical and continuous data

Fast and accurate for diagnosis tasks

🔹 Dataset

📍 UCI Heart Disease Dataset
Dynamic values including:


testdata

age, sex, cp, trestbps, chol, fbs,
restecg, thalach, exang, oldpeak, slope, ca, thal

🔹 Model Training Process
Step	Task
Data Preprocessing	Handle missing values & scaling
Feature Encoding	Convert categorical medical terms to numeric
Train-Test Split	Separate data for evaluation
Naïve Bayes Model Training	Learn patterns from dataset
Model Saving	Used by Django backend to predict in real-time
🧑‍💻 Technologies Used
Category	Tools Used
Web Framework	Django (Confirmed by manage.py) 

manage


Programming Language	Python
Machine Learning	Naïve Bayes (sklearn)
Data Handling	Pandas, NumPy
Front-End UI	HTML, CSS, Bootstrap
Database	Django Default SQLite (user login + profile)
Visualization (optional)	Matplotlib / Seaborn
🔐 User Authentication

📌 Information stored in database table:

username, password, contact, email, address


✔ Prevents unauthorized access
✔ Supports login session management
✔ Confirmed via session.txt 

session

🧾 Output Example

After entering patient health data → model predicts:

➡️ Result: Chance of Heart Disease — HIGH
OR
➡️ Result: No Heart Disease Risk Detected

✔ Clean & easy-to-understand result
✔ No medical background needed

🏥 Real World Applications

Hospital Diagnosis Support System

Telemedicine Platforms

Mobile Health Predictive Applications

Wellness Clinics & Labs

🧩 System Advantages
Benefit	Explanation
Early Detection	Prevents serious conditions early
Web Based Access	Any system with browser can use it
Cost Efficient	No additional medical devices
Fast Prediction	Works in less than 1 second
Data Security	User login + encrypted storage
🚀 Future Enhancements
Upgrade	Impact
Deep Learning Model (ANN/CNN)	Boost accuracy
Doctor Dashboard	Medical supervision
Report Generation (PDF)	Patient analysis records
Wearable Device Data Integration	Real-time health monitoring
Cloud Deployment	Universal access for hospitals
✨ Conclusion

This project demonstrates how Artificial Intelligence can save lives through smart disease prediction. Machine learning models help identify heart patients at early stages and support real-time diagnosis.

It is a successful implementation of:

AI in Healthcare

Full-stack Web Development

Predictive Analytics

✔ Smart
✔ Scalable
✔ Practical
✔ Industry-useful Project 
