This project implements supervised machine learning models to predict diabetes diagnosis and blood glucose levels using medical data.

The goal is to analyze the relationship between patient characteristics and diabetes risk, and to evaluate the performance of different regression and classification models.

The project was developed as part of a Machine Learning assignment and implemented in Python using Google Colab.

## Dataset

The dataset contains medical diagnostic measurements from 768 patients.

Features include:

- Pregnancies
- Glucose concentration
- Blood Pressure
- Skin Thickness
- Insulin level
- Body Mass Index (BMI)
- Diabetes Pedigree Function
- Age

Target variable:

- Outcome (0 = No diabetes, 1 = Diabetes)

- ## Project Structure

Part 1 – Logistic Regression
- Data exploration and visualization
- Feature statistics (mean, std, min, max)
- Histograms and bar plots
- Train-test split (70-30)
- Logistic Regression classifier
- Model evaluation (accuracy)
- Performance comparison across age groups
- Feature normalization (Min-Max scaling)
- Identification of most important features

Part 2 – Linear Regression
- Prediction of glucose levels using limited medical inputs
- Linear Regression model
- Evaluation using regression metrics
- Lasso Regression with different regularization strengths
- Feature importance analysis

- ## Technologies Used

Python

Libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

- ## Evaluation Metrics

Classification:
- Accuracy score

Regression:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
