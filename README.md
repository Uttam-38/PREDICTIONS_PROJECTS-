# PREDICTIONS_PROJECTS-
This project uses machine learning to predict loan eligibility based on user-provided information. It leverages an XGBoost classifier trained on key financial and demographic factors, with a user-friendly command-line interface that provides eligibility predictions and actionable recommendations for improving eligibility.

Project Overview

This application predicts whether a loan applicant is eligible for a loan based on six input factors:

Age
Job type
Account balance
Housing ownership
Existing loans
Duration of last contact with the bank
If the applicant is found ineligible, the program offers recommendations for improving eligibility, such as increasing their account balance or paying off existing loans.

Features

Machine Learning Model: Uses an XGBoost classifier to predict loan eligibility based on selected features.
User Input: Takes user input for key factors, validates entries, and applies preprocessing steps to match the training data.
Recommendations: Provides customized recommendations to improve eligibility for those initially ineligible.
Model Performance: Displays model evaluation metrics including AUC-ROC and F1 Score, along with an ROC Curve plot for visual inspection.
Installation

Prerequisites
This project requires Python 3.7+ and the following Python libraries:

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

Future Improvements

Feature Engineering: Experiment with additional features and feature interactions.
Model Persistence: Save the trained model for faster predictions without retraining.
Enhanced Input Validation: Add more detailed validation for user inputs.
User Interface: Consider developing a web-based interface for a more accessible user experience.
License

This project is licensed under the MIT License.
