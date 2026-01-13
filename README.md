# Student Performance Prediction System

## Overview
This project predicts student academic outcomes using machine learning
classification models. The goal is to identify at-risk students early
so academic advisors can take proactive action.

## Dataset
The dataset contains demographic, behavioral, and academic information
about students.

Target variable:
- Outcome (0 = At Risk, 1 = Successful)

## Models Used
- Logistic Regression
- Decision Tree
- Random Forest

## Techniques Applied
- Categorical feature encoding
- Feature scaling using StandardScaler
- Feature engineering
- Handling class imbalance using SMOTE
- Hyperparameter tuning using GridSearchCV
- Model evaluation using accuracy, classification report, and confusion matrix

## Results
The Random Forest model performed best with strong classification accuracy.
Feature importance analysis highlighted key factors influencing student success.

## How to Run
1. Clone the repository
2. Install dependencies:
3. 3. Open `student_performance_prediction.ipynb`
4. Run all cells

## Future Improvements
- Add real-time prediction API
- Improve feature engineering
- Integrate dashboard visualization

## Author
Nikhil Tummala

