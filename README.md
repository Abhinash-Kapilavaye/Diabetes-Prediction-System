# Diabetes Prediction System

## Project Overview
A machine-learning web application that predicts diabetes status using a Random Forest classification model. The application accepts health-related inputs through a Flask web interface and displays the model's prediction.

## Technologies Used
- Python
- Pandas and NumPy
- Scikit-learn
- Random Forest Classifier
- Flask
- HTML and CSS

## Features
- User-friendly web form
- Eight health-related input features
- Machine-learning-based classification
- Prediction results displayed on the website

## Project Structure
```text
Diabetes-Prediction-System/
├── app.py
├── templates/
│   └── index.html
├── diabetes_model.pkl
├── requirements.txt
├── .gitignore
└── README.md
```

## Installation and Usage
1. Clone this repository.
2. Create and activate a Python virtual environment.
3. Install the required packages using `pip install -r requirements.txt`.
4. Ensure the trained model file is available.
5. Run `python app.py`.
6. Open `http://127.0.0.1:5000` in your browser.

## Disclaimer
This project is for educational purposes only. Its predictions are not a medical diagnosis and should not replace professional medical advice.
