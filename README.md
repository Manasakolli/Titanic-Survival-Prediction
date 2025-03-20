# Titanic Survival Prediction

## Project Overview
This project develops a machine learning model to predict whether a passenger survived the Titanic disaster. The dataset includes features like age, gender, ticket class, and fare. The goal is to preprocess the data, train a model, and evaluate its performance.

## Preprocessing Steps
1. **Load Data**: Read the Titanic dataset.
2. **Drop Irrelevant Columns**: Remove `PassengerId`, `Name`, `Ticket`, and `Cabin`.
3. **Handle Missing Values**:
   - `Age` is filled with the median.
   - `Fare` is filled with the mean.
4. **Encode Categorical Variables**:
   - `Sex`: Male = 1, Female = 0.
   - `Embarked`: Label encoded.
5. **Normalize Numerical Features**: `Age` and `Fare` are scaled using `StandardScaler`.
6. **Split Data**: The dataset is split into training (80%) and testing (20%) sets.

## Model Selection & Evaluation
- **Model Used**: Random Forest Classifier (100 estimators, random state = 42).
- **Performance Metrics**:
  - Accuracy
  - Precision
  - Recall
  - F1 Score

## Results
The trained model achieves the following performance:
Accuracy: 1.0
Precision: 1.0
Recall: 1.0
F1 Score: 1.0

Predicts whether the passanger is survived or not
