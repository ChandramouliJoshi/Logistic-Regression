# Titanic Survival Prediction Using Logistic Regression

Predicting passenger survival on the Titanic using a Logistic Regression model with the Kaggle Titanic dataset.

## Project Overview
- **Goal:** Predict whether a passenger survived based on features like Age, Sex, Fare, and Embarked.  
- **Dataset:** `train.csv`, `test.csv`, `gender_submission.csv` from Kaggle.  
- **Preprocessing:** Filled missing values, encoded categorical variables, scaled features.  
- **Model:** Logistic Regression trained on processed training data.  
- **Evaluation:** Training accuracy, confusion matrix, classification report, and feature importance visualization.  

## Features
- **Feature Importance Plot:** See which features impact survival predictions the most.  
- **Survival Probabilities:** Model outputs probabilities for each passenger.  
- **Submission Ready:** CSV file formatted for Kaggle submission.  

## Output
- `Survivors.png` → Feature importance bar chart  
- `Survival_Probabilities.png` → Histogram of predicted survival probabilities  
- `titanic_submission.csv` → Predicted survival for test set  

## How to Run
1. Clone the repository:  
```bash
git clone https://github.com/ChandramouliJoshi/Logistic-Regression.git
