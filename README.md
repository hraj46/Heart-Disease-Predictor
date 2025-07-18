# ❤️ Heart Disease Predictor Web App

This is a machine learning-based web application that predicts the likelihood of heart disease using a Logistic Regression model. The app allows users to input basic health parameters and get real-time predictions.

---

## 🔍 Project Overview

The goal of this project is to build a lightweight, responsive, and user-friendly interface for heart disease prediction. The backend is powered by a trained Logistic Regression model using Scikit-learn, while the frontend is built with HTML, CSS, and JavaScript (AJAX).

---

## 🛠️ Features

- Logistic Regression model trained on `heart.csv` dataset
- Predicts heart disease based on:
  - Age
  - Chest Pain Type (cp)
  - Max Heart Rate Achieved (thalach)
- Responsive and attractive UI
- AJAX-powered real-time prediction
- Background image and styling for better UX
- Keeps form values intact after prediction

---

## 📂 Project Structure
```
├── app.py # Flask backend
├── heart_disease_model.pkl # Trained ML model
├── requirements.txt # Python dependencies
├── static/
│ └── styles.css # Custom CSS
│ └── background.jpg # Background image
└── templates/
└── index.html # Frontend HTML
```

---

## 🚀 How to Run the App Locally

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/heart-disease-predictor.git
cd heart-disease-predictor
```
2. **Create a virtual environment (optional but recommended)**
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
3. **Install dependencies**
```bash
pip install -r requirements.txt
```
4. **Run the Flask app**
```bash
python app.py
```
Open in Browser
Go to http://localhost:5000

---

🧠 Model Info
Algorithm: Logistic Regression

Input Features: Age, Chest Pain Type (cp), Maximum Heart Rate Achieved (thalach)

Target: 1 = Heart disease present, 0 = No heart disease

📦 Requirements
Python 3.7+

Flask

scikit-learn

pandas

numpy

joblib

🙋‍♂️ Author
Himanshu Raj
LinkedIn | GitHub

## 📄 License
This project is open-source and available under the MIT License.

yaml
Copy
Edit

Let me know if you want me to personalize it further with your GitHub link, profile photo, or dataset credits!
