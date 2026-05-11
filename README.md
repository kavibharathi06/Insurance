# Insurance deployment link :https://insurance-crzdt4wtztgc2xo6fhxsyw.streamlit.app/

# Insurance Prediction App

A simple Machine Learning web application built using Streamlit that predicts whether a person will buy insurance based on their age.

The project demonstrates:
- Linear Regression
- Logistic Regression
- Data Visualization
- Streamlit UI

---

# Technologies Used

- Python
- Streamlit
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

# Dataset

The dataset file used is:

insurance_data.csv

Columns:
- age
- bought_insurance

Example:

| age | bought_insurance |
|-----|------------------|
| 22  | 0 |
| 25  | 0 |
| 47  | 1 |

Where:
- 0 = Did Not Buy Insurance
- 1 = Bought Insurance

---

# Features

✔ Predicts insurance purchase using Logistic Regression

✔ Displays model accuracy

✔ Interactive age slider

✔ Shows probability of buying insurance

✔ Visualizes:
- Scatter Plot
- Linear Regression Line
- Logistic Regression Curve

---

# Project Structure

project_folder/
│
├── app.py
├── insurance_data.csv
└── README.md

---

# Installation

## Step 1: Install Python

Download Python:
https://www.python.org/downloads/

---

## Step 2: Install Required Libraries

Open terminal or command prompt and run:

pip install streamlit pandas matplotlib numpy scikit-learn

---

# Run the Application

Inside the project folder, run:

streamlit run app.py

---

# Output

The app will open in your browser.

You can:
- Select age using slider
- View prediction result
- Check probability percentage
- View regression graphs

---

# Machine Learning Models Used

## 1. Linear Regression

Used for:
- Drawing prediction trend line

## 2. Logistic Regression

Used for:
- Classification
- Predicting insurance purchase

---

# Accuracy Calculation

The model accuracy is calculated using:

accuracy_score()

---

# Graphs Included

## Scatter Plot
Displays actual dataset points.

## Linear Regression Graph
Shows linear prediction line.

## Logistic Regression Curve
Shows probability curve with prediction point.

---

# Author

Developed using Python and Streamlit for Machine Learning practice.
