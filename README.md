                                                                              Titanic Survival Prediction

This project aims to predict the survival of passengers aboard the Titanic using machine learning techniques. It leverages the well-known Titanic dataset, which includes various features such as age, gender, class, and more.

Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Features](#features)
- [Modeling](#modeling)
- [Results](#results)
- [Conclusion](#conclusion)

Overview
The Titanic Survival Prediction project uses the Titanic dataset to create a predictive model for passenger survival. The goal is to apply different machine learning algorithms and compare their performance to find the best model for this task.

Dataset
The dataset used in this project is provided by Kaggle.

Features
The dataset includes the following features:
- `PassengerId`: Unique ID for each passenger
- `Survived`: Survival (0 = No, 1 = Yes)
- `Pclass`: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- `Name`: Passenger name
- `Sex`: Gender
- `Age`: Age in years
- `SibSp`: Number of siblings / spouses aboard the Titanic
- `Parch`: Number of parents / children aboard the Titanic
- `Ticket`: Ticket number
- `Fare`: Passenger fare
- `Cabin`: Cabin number
- `Embarked`: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

Modeling
This project explores various machine learning models, including:
- Logistic Regression
- Decision Trees
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

Each model is evaluated based on accuracy, precision, recall, and F1-score.

Results
The performance of each model is summarized in the following table:

| Model               | Accuracy | Precision | Recall | F1-Score |
|---------------------|----------|-----------|--------|----------|
| Logistic Regression | 0.78     | 0.76      | 0.70   | 0.73     |
| Decision Tree       | 0.77     | 0.74      | 0.71   | 0.72     |
| Random Forest       | 0.80     | 0.79      | 0.74   | 0.76     |
| SVM                 | 0.79     | 0.77      | 0.72   | 0.74     |
| KNN                 | 0.76     | 0.74      | 0.68   | 0.71     |

Conclusion
The Random Forest model achieved the highest accuracy and overall performance for predicting Titanic survival. Further improvements could be made by tuning hyperparameters and exploring additional features.
