# ❤️ Heart Disease Prediction using Machine Learning

## Project Overview

This project is a Heart Disease Prediction System developed using Python, Machine Learning, and Flask. It predicts whether a person is likely to have heart disease based on medical parameters entered by the user. The model is trained using the Random Forest Classifier and deployed as a web application using Flask.

---

## Student Information

**Name:** Akanksha Choudhary

**Roll Number:** 240603010069

**Course:** B.Tech Computer Science & Engineering

**College:** Government Degree College Dharamshala

---

## Objectives

- Predict the possibility of heart disease using machine learning.
- Provide a simple and user-friendly web interface.
- Help users understand their heart disease risk based on medical data.

---

## Technologies Used

- Python
- Jupyter Notebook
- Flask
- HTML
- CSS
- Pandas
- NumPy
- Scikit-learn
- Joblib

---

## Machine Learning Algorithm

**Random Forest Classifier**

Random Forest is an ensemble machine learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

---

## Dataset

Dataset Name: **heart.csv**

The dataset contains **1025 patient records** and **14 columns**.

### Input Features

- Age
- Sex
- Chest Pain Type (cp)
- Resting Blood Pressure (trestbps)
- Cholesterol (chol)
- Fasting Blood Sugar (fbs)
- Rest ECG (restecg)
- Maximum Heart Rate (thalach)
- Exercise Induced Angina (exang)
- Oldpeak
- Slope
- Number of Major Vessels (ca)
- Thal

### Target

- **0** = No Heart Disease
- **1** = Heart Disease

---

## Project Structure

```
Heart_Disease_Prediction/
│
├── Heart_Disease_Prediction.ipynb
├── train_model.py
├── app.py
├── model.pkl
├── heart.csv
├── requirements.txt
├── README.md
│
├── templates/
│   └── index.html
│
└── static/
    └── style.css
```

---

## How to Run the Project

### Step 1

Install the required libraries.

```
pip install -r requirements.txt
```

### Step 2

Train the model.

```
python train_model.py
```

### Step 3

Run the Flask application.

```
python app.py
```

### Step 4

Open your browser and visit:

```
http://127.0.0.1:5000
```

---

## Features

- User-friendly web interface
- Heart disease prediction
- Random Forest Machine Learning model
- Fast prediction
- Easy to use
- Flask web application

---

## Project Workflow

1. Load Dataset
2. Data Preprocessing
3. Split Dataset
4. Train Random Forest Model
5. Evaluate Model
6. Save Model
7. Deploy Using Flask
8. Predict Heart Disease

---

## Future Improvements

- Improve prediction accuracy using advanced algorithms.
- Add graphical data visualization.
- Connect with a real-time database.
- Deploy the application online.

---

## Conclusion

This project demonstrates how Machine Learning can be used in the healthcare field to predict heart disease. The Random Forest model provides accurate predictions, while Flask offers an easy-to-use web interface for users.

---

## Author

**Akanksha Choudhary**

B.Tech Computer Science & Engineering

Government Degree College Dharamshala

Roll No.: 240603010069