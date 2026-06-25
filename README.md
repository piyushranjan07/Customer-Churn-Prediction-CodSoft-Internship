# Customer-Churn-Prediction-CodSoft-Internship

## Overview

Customer churn prediction is the process of identifying customers who are likely to stop using a company's services. This project uses Machine Learning techniques to predict customer churn based on customer demographics, account information, and usage behavior.

## Objective

The objective of this project is to build a classification model that can predict whether a customer will leave the company (churn) or continue using the services.

## Dataset

The dataset contains customer information such as:

* Credit Score
* Geography
* Gender
* Age
* Tenure
* Balance
* Number of Products
* Has Credit Card
* Is Active Member
* Estimated Salary
* Exited (Target Variable)

### Target Variable

* 0 → Customer Stayed
* 1 → Customer Churned

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Google Colab

## Project Workflow

### 1. Data Collection

The customer churn dataset is loaded from a CSV file.

### 2. Data Preprocessing

* Removed unnecessary columns

  * RowNumber
  * CustomerId
  * Surname
* Encoded categorical variables
* Checked for missing values

### 3. Feature Selection

Input features were separated from the target variable (Exited).

### 4. Train-Test Split

The dataset was divided into:

* 80% Training Data
* 20% Testing Data

### 5. Model Training

A Random Forest Classifier was used for training the model.

### 6. Prediction

The trained model predicts whether a customer will churn or not.

### 7. Model Evaluation

The model performance was evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix

## Results

The model successfully predicts customer churn with good accuracy.

Evaluation Metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

## Feature Importance

Feature importance analysis was performed to identify the factors that most influence customer churn.

## Future Improvements

* Hyperparameter Tuning
* Cross Validation
* Gradient Boosting Models
* XGBoost Implementation
* Deployment using Flask or Streamlit

## Conclusion

Customer churn prediction helps businesses identify customers who are likely to leave and take proactive actions to improve customer retention. This machine learning model provides a useful solution for predicting customer behavior and supporting business decision-making.

## Author

Piyush Ranjan

### Internship

CODSOFT Machine Learning Internship

#MachineLearning #CustomerChurnPrediction #Python #RandomForest #CODSOFT

