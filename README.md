# Insurance Purchase Prediction using Logistic Regression

## Project Overview

The Insurance Prediction App is a Machine Learning-based web application developed using Streamlit. The application predicts whether a customer is likely to purchase insurance based on their age. The project demonstrates the implementation of Linear Regression and Logistic Regression techniques along with data visualization.

This project was developed to understand predictive analytics, classification algorithms, model evaluation, and interactive web application deployment using Python.

---

## Objectives

* To predict customer insurance purchase behavior.
* To understand Logistic Regression for binary classification.
* To visualize prediction trends using regression graphs.
* To build an interactive Machine Learning application using Streamlit.

---

## Technologies Used

| Technology   | Purpose                   |
| ------------ | ------------------------- |
| Python       | Programming Language      |
| Streamlit    | Web Application Framework |
| Pandas       | Data Handling             |
| NumPy        | Numerical Operations      |
| Matplotlib   | Data Visualization        |
| Scikit-learn | Machine Learning Models   |

---

## Dataset Information

The dataset used for this project contains customer age details and insurance purchase information.

### Dataset Columns

| Column Name      | Description               |
| ---------------- | ------------------------- |
| age              | Age of customer           |
| bought_insurance | Insurance purchase status |

### Target Variable

* 1 → Bought Insurance
* 0 → Did Not Buy Insurance

---

## Machine Learning Models Used

### Linear Regression

Used to visualize the relationship between age and insurance purchase trends.

### Logistic Regression

Used for binary classification to predict whether a customer will purchase insurance.

---

## Project Workflow

1. Load the dataset using Pandas.
2. Split the dataset into training and testing sets.
3. Train Linear Regression and Logistic Regression models.
4. Evaluate model performance using accuracy score.
5. Build an interactive Streamlit interface.
6. Display prediction results and graphical visualizations.

---

## Features

* Interactive age selection using slider.
* Insurance purchase prediction.
* Probability estimation.
* Accuracy score display.
* Scatter Plot visualization.
* Linear Regression graph.
* Logistic Regression curve.

---

## Data Visualizations

### Scatter Plot

Displays the relationship between age and insurance purchase.

### Linear Regression Graph

Shows the linear trend between age and prediction values.

### Logistic Regression Curve

Displays the probability curve for insurance purchase prediction.

---

## Model Evaluation

The Logistic Regression model accuracy is calculated using the `accuracy_score()` function from Scikit-learn.

---

## Project Structure

```bash
Insurance_Prediction_Project/
│
├── app.py
├── insurance_data.csv
├── README.md
└── requirements.txt
```

---

## Installation

### Install Required Libraries

```bash
pip install streamlit pandas numpy matplotlib scikit-learn
```

### Run the Application

```bash
streamlit run app.py
```

---

## Conclusion

This project demonstrates the practical implementation of Machine Learning algorithms for predictive analytics. It provides a beginner-friendly understanding of Logistic Regression, data visualization, and Streamlit-based application development.
