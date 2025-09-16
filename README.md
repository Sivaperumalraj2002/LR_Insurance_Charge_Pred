Insurance Charges Prediction using Linear Regression
📌 Project Overview

This project focuses on building a Linear Regression model to predict insurance charges for customers based on demographic, lifestyle, health, and financial factors. The dataset consists of 1338 records and 13 features, and the model achieved an impressive 97% accuracy (R² score).

This project demonstrates how Machine Learning can bring value to the insurance industry by enabling better cost prediction, risk assessment, and decision-making.

🗂 Dataset

The dataset contains the following features:

age: Age of the insured individual

sex: Gender of the insured

bmi: Body Mass Index

children: Number of children/dependents covered by insurance

smoker: Smoking status (yes/no)

Claim_Amount: Claim amount raised

past_consultations: Number of past consultations

num_of_steps: Steps taken (lifestyle activity)

Hospital_expenditure: Historical hospital expenditure

NUmber_of_past_hospitalizations: Count of past hospitalizations

Anual_Salary: Annual salary of the insured

region: Residential region (northeast, northwest, southeast, southwest)

charges: Target variable (insurance charges)

⚙️ Tech Stack

Programming Language: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

🔬 Approach

Data Preprocessing

Handled missing values and outliers

Encoded categorical features (sex, smoker, region)

Scaled numerical features for better regression performance

Exploratory Data Analysis (EDA)

Correlation heatmap to understand feature importance

Distribution analysis of charges and other key variables

Model Development

Implemented Linear Regression using Scikit-learn

Split dataset into train and test sets (80/20 split)

Model Evaluation

Achieved 97% R² score

Evaluated using RMSE and MAE

Visualized Actual vs Predicted charges

📊 Results

Accuracy (R² Score): 97%

The model successfully captured the relationship between demographic, lifestyle, and health-related attributes with insurance charges.
