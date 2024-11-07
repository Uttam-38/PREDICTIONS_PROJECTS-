# PREDICTIONS_PROJECTS-

**THERE ARE TWO PREDICIOTNS LISTED :**
**1. CUSTOMER LOAN PREDICTION**
**2. HOUSE PRICE PREDICTION**


This project uses machine learning to predict loan eligibility based on user-provided information. It leverages an XGBoost classifier trained on key financial and demographic factors, with a user-friendly command-line interface that provides eligibility predictions and actionable recommendations for improving eligibility.

**Project Overview**

This application predicts whether a loan applicant is eligible for a loan based on six input factors:

1. Age

2. Job type

3. Account balance

4. Housing ownership

5. Existing loans
   
6. Duration of last contact with the bank
If the applicant is found ineligible, the program offers recommendations for improving eligibility, such as increasing their account balance or paying off existing loans.

**Features**

Machine Learning Model: Uses an XGBoost classifier to predict loan eligibility based on selected features.
User Input: Takes user input for key factors, validates entries, and applies preprocessing steps to match the training data.
Recommendations: Provides customized recommendations to improve eligibility for those initially ineligible.
Model Performance: Displays model evaluation metrics including AUC-ROC and F1 Score, along with an ROC Curve plot for visual inspection.
Installation

**Prerequisites** This project requires Python 3.7+ and the following Python libraries:

pandas
scikit-learn
xgboost
matplotlib 
Project Structure

loan_prediction.py: Main script for running the prediction model and obtaining user input.
train.csv: Training data file (user must provide).
test.csv: Test data file (user must provide).
README.md: Project documentation.
Model Evaluation

The model performance is evaluated using AUC-ROC and F1 Score. An ROC curve is also generated to visually inspect the model’s classification performance.

**Future Improvements**

Feature Engineering: Experiment with additional features and feature interactions.
Model Persistence: Save the trained model for faster predictions without retraining.
Enhanced Input Validation: Add more detailed validation for user inputs.
User Interface: Consider developing a web-based interface for a more accessible user experience. 

**License**

This project is licensed under the MIT License.






**HOUSE PRICE PREDICTIONS** 
This project predicts house prices based on several key factors like area, bedrooms, bathrooms, and more. The models used in this project include Decision Tree, Bagging Regressor, and Support Vector Machine (SVM) for regression. The objective is to help users estimate house prices accurately using machine learning models trained on historical housing data.

**Project Overview**

This repository contains code and resources for predicting house prices using machine learning. The project focuses on applying regression algorithms to analyze key features impacting house prices.

**Key objectives:**

Develop multiple regression models for comparison.
Identify important features affecting house prices.
Provide an interactive way for users to input values and predict house prices.
Data

**The dataset used in this project includes various features relevant to housing prices, such as:**

1. area: The area of the property in square feet.
  
2. bedrooms: Number of bedrooms.

3. bathrooms: Number of bathrooms.

4. stories: Number of stories in the property.

5. parking: Availability of parking spaces.

And other categorical and continuous features that influence housing prices.
Models and Algorithms

**The project explores the following algorithms:**

Decision Tree Regressor: A model that splits data based on feature importance.
Bagging Regressor: An ensemble technique that combines predictions from multiple decision trees.
Support Vector Machine (SVM) Regressor: A model that tries to find a hyperplane to fit the data optimally.
Each model is evaluated to determine which one yields the most accurate predictions.

**Evaluation Metrics**

The models are evaluated using the following metrics:

**Root Mean Squared Error (RMSE):** Measures the average deviation of predictions from actual values.
**F1 Score (for classification tasks if needed):** Not applicable for pure regression but can be computed if categorical price ranges are predicted.
**ROC Curve (for classification tasks if needed):** Not directly used for regression models; however, it can apply if the task is modified to predict price categories.
