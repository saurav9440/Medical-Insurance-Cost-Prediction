#### Medical Insurance Cost Prediction
### Project Overview
This project focuses on building a machine learning model to predict individual medical insurance costs. The goal is to develop an accurate predictive system that helps insurance companies and individuals estimate expenses based on key health and demographic factors. This project demonstrates a complete machine learning workflow, from data analysis and preprocessing to model training and evaluation.

### Dataset
The dataset used is the Medical Cost Personal Dataset, publicly available on Kaggle. It contains 1338 rows and 7 columns, including:

# age: Age of the primary beneficiary.

# sex: Gender (male/female).

# bmi: Body Mass Index.

# children: Number of children/dependents.

# smoker: Smoking status (yes/no).

# region: The beneficiary's residential area in the US.

# charges: Individual medical costs billed by health insurance (the target variable).

## Key Features & Techniques
Exploratory Data Analysis (EDA): Visualized data distributions and relationships to understand the impact of features like age, smoking status, and BMI on insurance charges.

Data Preprocessing: Handled categorical variables using OneHotEncoder and addressed the skewed distribution of the target variable by applying a logarithmic transformation.

Model Training: Trained and evaluated multiple regression models, including Linear Regression and advanced ensemble methods.

Model Selection: Selected a Gradient Boosting Regressor as the final model due to its superior performance in capturing non-linear relationships.

## Performance Metrics
The Gradient Boosting Regressor achieved the following results on the test set:

R-squared (R 
2
 ): 0.87 (The model explains 87% of the variance in insurance charges.)

Root Mean Squared Error (RMSE): $4480.40 (The average difference between the predicted and actual charges is approximately $4480.)

### Technologies Used
## Python

## Pandas

## NumPy

## Scikit-learn

## Matplotlib

## Seaborn
