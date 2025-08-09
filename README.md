# Hotel Booking Cancellation Prediction 🏨📊

This machine learning project analyzes hotel booking data and predicts whether a reservation is likely to be canceled. The goal is to help hotels anticipate no-shows and improve resource planning.

## 📁 Project Structure

- `hotel_booking-3.ipynb`: Main Jupyter Notebook with data analysis, feature engineering, model training, and evaluation
- `hotel_bookings.csv` (not included): Dataset used for model training
- `README.md`: Project overview and instructions

## 📊 Dataset Overview

The dataset includes historical booking information for a city hotel and a resort hotel, with features such as:

- Booking dates
- Number of adults, children, and babies
- Meal plans and market segment
- Lead time, deposit type, previous cancellations
- Assigned room type and special requests

**Target Variable:**  
`is_canceled` – Binary label indicating whether a booking was canceled (1) or not (0)

## 🔍 Objectives

- Explore and clean the dataset
- Visualize key booking patterns
- Engineer useful features
- Train predictive models (e.g., Logistic Regression, Decision Tree, Random Forest)
- Evaluate performance using accuracy, precision, recall, and confusion matrix

## 🧠 Methods Used

- Exploratory Data Analysis (EDA) with pandas & matplotlib/seaborn
- Data preprocessing & encoding (One-Hot Encoding, Label Encoding)
- Classification Models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
- Model evaluation (confusion matrix, classification report, ROC-AUC)



## ⚙️ Requirements

- Python 3.7+
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- Jupyter Notebook


