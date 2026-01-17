# Heart Disease Prediction

**Machine Learning-Based System for Early Detection and Prediction of Heart Disease**

---

## Project Overview

Heart disease is one of the leading causes of mortality worldwide. Early detection is crucial for timely medical intervention and improving patient outcomes. This project implements a **machine learning-based system** to predict the risk of heart disease using patient clinical data.

The system compares multiple supervised learning algorithms to determine the most accurate model, and then deploys it as a **user-friendly web application** using Flask, enabling medical professionals and users to assess heart disease risk in real-time.

---

## Dataset

- **Source:** Kaggle Heart Disease Dataset  
- **Size:** 1,025 patient records  
- **Attributes:** 14 clinical features including age, sex, cholesterol levels, blood pressure, and target label (presence or absence of heart disease)  
- **Usage:** Data preprocessing, feature engineering, model training, and evaluation

---

## Machine Learning Models Used

The following algorithms were implemented and evaluated:

| Model                    | Description                                         |
|---------------------------|-----------------------------------------------------|
| Logistic Regression       | Baseline linear classification model               |
| Random Forest Classifier  | Ensemble method achieving highest accuracy         |
| Decision Tree             | Tree-based classification model                     |
| K-Nearest Neighbors (KNN) | Distance-based classification                        |
| Naïve Bayes               | Probabilistic model for prediction                  |
| Support Vector Machine    | High-dimensional classifier with kernel methods    |

**Best Performing Model:** Random Forest (highest precision, accuracy, and reliability)

---

## Project Workflow

1. **Data Collection & Preprocessing**
   - Cleaned missing values
   - Scaled and normalized features
   - Performed exploratory data analysis

2. **Feature Engineering**
   - Selected important features influencing heart disease risk
   - Applied correlation analysis for feature selection

3. **Model Training & Evaluation**
   - Trained all models on the dataset
   - Evaluated performance using accuracy, precision, recall, and F1-score
   - Selected Random Forest as the optimal model

4. **Deployment**
   - Developed a Flask-based web application
   - Input: patient clinical parameters
   - Output: real-time heart disease risk prediction
   - User-friendly interface suitable for medical practitioners

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/Heart-Disease-Prediction.git
