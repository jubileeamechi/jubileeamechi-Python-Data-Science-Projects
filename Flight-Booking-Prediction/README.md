# ✈️ Flight Booking Prediction

This project explores whether a customer is likely to book a flight based on various personal and behavioral features. It applies machine learning techniques to predict customer booking patterns, which can be used to improve airline marketing strategies and customer targeting.

---

## 📊 Problem Statement

Airline companies often deal with uncertainty when predicting whether a potential customer will book a flight. This project solves a classification problem using machine learning to predict whether a customer will book a flight or not, based on features such as:

- Age
- Gender
- Location
- Travel history
- Booking history
- Class preference, and more.

---

## 🧠 Objectives

- Understand key patterns that influence customer bookings.
- Train and evaluate machine learning models (like Logistic Regression, Random Forest, etc.).
- Provide actionable insights based on prediction results.
- Visualize feature importance and model performance.

---

## 📁 Dataset

The dataset was cleaned and preprocessed from a customer_booking.csv file :

| Column | Description |
|--------|-------------|
| Age | Age of the customer |
| Gender | Male/Female |
| Trip_Type | One-way, Round-trip |
| Class | Economy/Business |
| Frequent_Flyer | Yes/No |
| ... | Additional relevant features |
| Booking_Status | **Target**: Booked / Not Booked |

---

## 🔧 Tools & Libraries

- **Python**
- **Pandas** – for data manipulation
- **Matplotlib & Seaborn** – for visualization
- **Scikit-learn** – for building ML models
- **Jupyter Notebook**

---

## ⚙️ Machine Learning Models Used

- Logistic Regression
- Decision Tree
- Random Forest
- Model Evaluation Metrics: Accuracy, Precision, Recall, Confusion Matrix

---

## 📌 Key Findings

- Certain features like **Trip Type**, **Frequent Flyer Status**, and **Class Preference** significantly impact booking behavior.
- Random Forest outperformed other models in terms of prediction accuracy.

---

## 📈 Project Highlights

- 🔍 Cleaned and explored data to understand booking trends.
- 🧠 Built and compared multiple machine learning models.
- 📉 Identified key predictors of booking likelihood.
- 📊 Visualized results using bar plots, confusion matrices, and feature importance.

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/jubileeamechi/Python-Data-Science-Projects.git
   cd Python-Data-Science-Projects/Flight-Booking-Prediction
