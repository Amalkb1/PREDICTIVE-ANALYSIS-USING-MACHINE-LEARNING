# PREDICTIVE-ANALYSIS-USING-MACHINE-LEARNING

# Titanic Survival Prediction


This project uses the Titanic dataset to predict passenger survival using machine learning techniques. The implementation includes data preprocessing, feature engineering, model training, and evaluation.


Overview

The Titanic dataset is a classic dataset used to explore binary classification problems. In this project, we predict whether a passenger survived the Titanic disaster using features such as age, gender, class, and more.

Steps in the Project
Import Libraries
Libraries used include:

pandas for data manipulation.
scikit-learn for model building and evaluation.
matplotlib for visualization.


Load Dataset

The dataset was loaded from Data Science Dojo's GitHub repository.


Data Preprocessing


Handled missing values for columns like Age and Embarked.
Dropped irrelevant features such as Cabin, Name, and Ticket.
Applied one-hot encoding for categorical variables (Sex, Embarked).


Feature Selection


Selected key features: Pclass, Sex, Age, SibSp, Parch, Fare, and Embarked.


Model Training



Split data into training and testing sets.
Trained a Random Forest Classifier for prediction.


Model Evaluation


Achieved an accuracy of 82.12% on the test dataset.
Generated a classification report to evaluate precision, recall, and F1-score.

Feature Importance


Analyzed the impact of features like Sex, Pclass, and Age on survival.

Key Insights

Gender: Females had a higher likelihood of survival.

Class: Passengers in higher classes (e.g., 1st class) had better survival rates.

Age: Younger passengers, particularly children, were more likely to survive.
