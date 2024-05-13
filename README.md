Machine Learning Project Documentation
Project Title: Medical Insurance Cost Prediction
Project Overview:
The goal of this project is to develop a machine learning model to predict medical costs for individual patients based on the collected features. Hospital ABC, a leading healthcare provider, aims to optimize its resource allocation and improve patient care by understanding the factors influencing medical costs for its patients. To achieve this, Hospital ABC has collected a comprehensive dataset containing information about patients' demographics, lifestyle, health status, and medical expenses etc. The dataset includes attributes such as age, gender, BMI, smoking status, region, as well as additional information like occupation, exercise frequency, chronic conditions, and more.
Project Timeline:
•	Start Date: 24-04-2024
•	End Date: 13-04-2024
Data Sources:
•	Customer demographic data (age, gender, income, etc.)
•	Service usage data (call duration, internet usage, etc.)
•	Customer churn status (churned or not churned)
Data Preprocessing:
1.	Handling Missing Values:
•	Imputed missing values in numerical features using median
•	Imputed missing values(less in number) in the categorical features using the mode.
•	Imputed missing values (high in number) in the categorical features using MICE algorithm
2.	: Encoding Categorical Features:
•	Applied One Hot Encoding for nominal categorical variables
•	Applied Label Encoding for ordinal categorical variables
3.	Feature Scaling:
•	Used standard scaler for scaling the values

4.	Data Splitting:
•	Split the preprocessed data into training (80%) and testing (20%) sets for model training and evaluation.
Exploratory Data Analysis (EDA):
•	Conducted EDA to understand the distribution of features, identify correlations, and visualize patterns in the data.
•	Plotted , box plots,barplot,scatterplot and correlation matrices to explore relationships between variables.
Model Building:
1.	Model Selection:
•	Experimented with multiple regression algorithms, including Linear Regression, Random Forest Regressor, Decision Tree Regressor and SVR
2.	Model Training:
•	Trained each model on the training dataset using feature selection techniques like SelectKbest, Lasso regression.

3.	Model Evaluation:
•	Evaluated model performance using metrics such as mean squared error, r2 score on the test dataset.
•	Selected the Random Forest regressor as the final model based on its superior performance.
Results:
•	Random Forest Classifier achieved an  r2 score 0.98 on the test dataset.
•	Feature importance analysis revealed that 'Age' and 'BMI' were the most significant predictors of Charges.
Conclusion:
The developed machine learning model demonstrates promising performance in predicting charges on medical insurance. 
Future Work:
•	Explore additional features or external datasets to improve model performance.
•	Deploy the model into production for real-time churn prediction and decision-making.
