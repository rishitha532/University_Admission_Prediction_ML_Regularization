# University_Admission_Prediction_ML_Regularization

Project Overview
The University Admission Prediction project is a Flask-based web application designed to predict the likelihood of admission to graduate programs based on individual student profiles. It employs various regression techniques, including Linear, Ridge, and Lasso regression, to analyze features such as GRE and TOEFL scores, university ratings, SOP and LOR strengths, CGPA, and research experience. This application aims to assist students in understanding their chances of getting into graduate school by leveraging machine learning for educational forecasting.

Independent Features
GRE Score: Test score for graduate school applications.
TOEFL Score: English proficiency test score.
University Rating: Rating of the university applied to.
SOP: Statement of purpose strength.
LOR: Strength of letters of recommendation.
CGPA: Undergraduate cumulative grade point average.
Research: Whether the student has research experience.

Algorithms Used
Linear Regression: Predicts continuous outcomes.
Ridge Regression: Reduces the model complexity, handles multicollinearity.
Lasso Regression: Performs the variable selection, improves prediction accuracy and in feature selection.

Steps Involved
Data Ingestion: Importing the dataset for analysis.
Data Preprocessing: Clean and prepare data.
Exploratory Data Analysis: Analyze data to find patterns.
Feature Engineering: Modify or create new features.
Model Building: Constructing the models to predict outcomes.
Model Evaluation: Assessing the model accuracy and performance.
Model Deployment: Deploying the model in a web application.

Commands Used
To install the dependencies:
pip install -r requirements.txt
To run the Flask Web Application:
python app.py

Contributing
Contributions to this project are welcome. Please fork the repository and submit a pull request.
