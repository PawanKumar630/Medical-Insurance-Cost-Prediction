1. Introduction

Healthcare expenses are increasing rapidly, making medical insurance an essential part of financial planning. Insurance companies determine policy charges based on several personal and medical factors. This project uses Machine Learning to predict medical insurance costs based on individual details such as age, BMI, smoking habits, and region.

The aim is to build a regression model that can estimate insurance charges accurately and identify the key factors influencing these costs.

2. Objective

The main objectives of this project are:

To analyze medical and demographic data

To identify major factors affecting medical insurance charges

To build a Machine Learning model for predicting insurance costs

To create an interactive system where users can input their details and receive predicted insurance charges

3. Dataset Description

The dataset used in this project is the Medical Cost Personal Dataset. It contains the following attributes:

Feature	Description
Age	Age of the individual
Sex	Gender of the individual
BMI	Body Mass Index
Children	Number of dependents covered
Smoker	Smoking habit (Yes/No)
Region	Residential area
Charges	Medical insurance cost (Target Variable)

The dataset contains 1338 records and does not have missing values.

4. Technologies and Libraries Used

This project is implemented using Python and the following libraries:

Python – Programming language

Pandas – Data handling and preprocessing

NumPy – Numerical operations

Matplotlib – Data visualization

Seaborn – Statistical visualization

Scikit-learn – Machine Learning modeling and evaluation

5. Machine Learning Concepts Used

The following ML concepts are applied in this project:

Supervised Learning

Regression

Feature Encoding (One-Hot Encoding)

Train-Test Split

Model Training and Prediction

Model Evaluation Metrics

6. Algorithm Used: Linear Regression

Linear Regression is used to predict continuous values by establishing a linear relationship between input features and the target variable (insurance charges).

Reasons for Choosing Linear Regression:

Simple and easy to understand

Suitable for numeric prediction

Provides insights into feature impact

7. Data Preprocessing

The following preprocessing steps were performed:

Loaded the dataset using Pandas

Checked for missing values

Converted categorical features into numeric format using one-hot encoding

Separated input features (X) and target variable (y)

Split the dataset into 80% training data and 20% testing data

8. Model Training

The Linear Regression model was trained using the training dataset. The model learned the relationship between features like age, BMI, smoking status, and insurance charges.

9. Model Evaluation

The model performance was evaluated using the following metrics:

Metric	Description
MAE (Mean Absolute Error)	Average prediction error
MSE (Mean Squared Error)	Squared prediction error
R² Score	Measures how well the model explains the variance in data

The model achieved a good R² score, indicating reasonable prediction performance.

10. Key Findings

Smoking significantly increases medical insurance costs

Higher BMI leads to higher insurance charges

Age is positively correlated with medical expenses

11. Interactive Prediction System

An interactive feature was implemented where users can enter their details (age, BMI, children, smoking status, gender, and region), and the system predicts the estimated insurance cost in real time.

12. Project Structure
Medical_Insurance_ML_Project
│
├── insurance.csv
├── Medical_Insurance_Prediction.ipynb

13. Conclusion

This project demonstrates how Machine Learning can be applied to predict medical insurance costs using personal and health data. The system provides useful insights into cost-driving factors and showcases a complete ML workflow from data preprocessing to real-time prediction.
