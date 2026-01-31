# Student-Marks-Prediction
Machine Learning model to predict student final marks
Student Marks Prediction Model
 Project Overview

This project implements a Machine Learning–based Student Marks Prediction System using Linear Regression.
The model predicts a student’s final marks based on academic and behavioral factors such as:

Study hours

Attendance percentage

Internal assessment marks

The objective of this project is to demonstrate the complete machine learning pipeline: data preparation, model training, evaluation, interpretation, and deployment readiness.

Problem Statement

Accurately predicting student academic performance can help educators:

Identify students who may need academic support

Understand which factors influence performance the most

Improve data-driven decision making in education

This project aims to build a regression model that can predict final marks using historical academic data.

Dataset Description

The dataset contains the following features:

Feature Name	Description
Study_Hours	Average number of hours a student studies per day
Attendance	Attendance percentage
Internal_Marks	Marks obtained in internal assessments
Final_Marks	Final exam marks (target variable)

The dataset is either manually created or loaded from a CSV file for demonstration purposes.

 Technologies & Libraries Used

Python

Pandas – data handling

NumPy – numerical operations

Scikit-learn – machine learning

Joblib – model serialization

Google Colab / Jupyter Notebook

⚙️ Methodology

Data loading and preprocessing

Feature selection and target separation

Train–test split (80% training, 20% testing)

Model training using Linear Regression

Model evaluation using R² score

Interpretation of feature coefficients

Saving the trained model for reuse

Model Performance

The model achieved an excellent performance:

R² Score (Test Data): ~0.99

This indicates that the model explains approximately 99% of the variance in final marks, demonstrating strong predictive capability and generalization.

Feature Importance Interpretation

The learned coefficients indicate that:

Internal_Marks have the strongest influence on final marks

Attendance has a moderate impact

Study_Hours contribute positively but with a smaller coefficient

This makes intuitive academic sense and validates the model behavior.

Example Prediction

The trained model can predict final marks for a new student given inputs such as:

Study Hours: 5

Attendance: 90%

Internal Marks: 42

The model outputs a predicted final score based on learned patterns.

 Saved Model

The trained model is saved as:

student_marks_prediction_model.pkl


This allows the model to be reused without retraining and enables deployment through scripts or applications.

 Project Structure
Student-Marks-Prediction/
│
├── student_marks_prediction_FINAL.ipynb
├── student_marks_prediction_model.pkl
├── README.md
└── student_marks.csv (optional)

 Future Improvements

Use larger and real-world datasets

Try advanced models (Random Forest, SVR)

Add a web interface using Streamlit

Deploy as an API using Flask or FastAPI

Include more academic and behavioral features

 Author

Kartik Goyal
B.Tech + MBA Tech (AI Pathway)
NMIMS MPSTME

 Conclusion

This project successfully demonstrates how machine learning can be applied to predict student performance using simple yet effective regression techniques. It highlights the importance of data-driven approaches in education and serves as a foundational ML project suitable for academic evaluation and portfolio building.

