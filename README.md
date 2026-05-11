# Model for heart disease detection

## Introduction

This project is aimed at predicting the likelihood of heart disease in individuals based on various health parameters. It involves data analysis, data preprocessing, and the application of machine learning models to make predictions.

## Objective
```
The main objective of this project is to create a predictive model that can help identify individuals at a higher risk of heart disease. By analyzing a dataset of health parameters, we aim to build accurate models that can assist in early detection and intervention.
```

## Brief Description of the Project

This project involves the analysis of a dataset containing various health parameters and a binary classification task to predict the presence or absence of heart disease in individuals. The project consists of the following major steps:
```
    1. Importing libraries and datasets.
    2. Data understanding and exploration.
    3. Data preprocessing and cleaning.
    4. Exploratory Data Analysis (EDA) to gain insights into the dataset.
    5. Feature selection and handling multicollinearity.
    6. Splitting the data into training and testing sets.
    7. Hyperparameter tuning for machine learning models.
    8. Model training and evaluation using three different algorithms: Logistic Regression, Decision Tree, and Support Vector Machine (SVM).
```

## Importing Libraries and Dataset

This project utilizes several Python libraries for data analysis, machine learning, and visualization. Key libraries include:
```
    - Pandas
    - NumPy
    - Seaborn
    - Scikit-learn
    - Matplotlib
    - PyTorch
```
The dataset used in this project is stored in a CSV file named 'heart.csv'.

## Factors or Parameters Considered from the CSV File

The following factors or parameters are considered from the CSV file:
```
-- 1. ID (unique identifier)
-- 2. age
-- 3. sex
-- 4. chest pain type (4 values)
-- 5. resting blood pressure
-- 6. serum cholestoral in mg/dl
-- 7. fasting blood sugar > 120 mg/dl
-- 8. resting electrocardiographic results (values 0,1,2)
-- 9. maximum heart rate achieved
-- 10. exercise induced angina
-- 11. oldpeak = ST depression induced by exercise relative to rest
-- 12. the slope of the peak exercise ST segment
-- 13. number of major vessels (0-3) colored by flourosopy
-- 14. thal: 3 = normal; 6 = fixed defect; 7 = reversable defect
```

## Steps Included in this Project
```
    1. Data loading and exploration.
    2. Data preprocessing, including handling outliers, missing values, and duplicates.
    3. Exploratory data analysis (EDA) to gain insights into the dataset.
    4. Feature selection based on correlation.
    5. Train-test split of the dataset.
    6. Hyperparameter tuning for multiple machine learning models:
    - Logistic Regression
    - Random Forest
    - Binary Neural Networks
    7. Model training and evaluation.
    8. Display of confusion matrices and classification reports for model performance.
```

##  Brief Description and Insight

This project aims to identify early indicators of heart disease by analyzing various health parameters. It involves data preprocessing to clean and prepare the data for analysis. Exploratory Data Analysis (EDA) provides valuable insights into the dataset, enabling us to make informed decisions regarding feature selection and model training.

The feature selection process involves considering parameters with significant influence on heart disease prediction and handling multicollinearity to ensure model accuracy. Hyperparameter tuning is performed to optimize the machine learning models' performance.
```
Three modelling procedures are employed in this project:
1. **Logistic Regression**: A widely used classification algorithm that estimates the probability of a binary outcome. Logistic Regression is used to predict the likelihood of heart disease. The model is trained with hyperparameters optimized through grid search.
2. **Random Forest**: Algorithm is a set of algorithm models demonstrating many decision trees using bootstrapping, random subsets of tools, and average voting to make predictions. For a classification issue, Random Forest provides the probability of belonging to the class.
3. **Binary Neural Networks**: A machine learning model that is used to assign objects to one of two classes based on their features.
```
The models are evaluated using confusion matrices and classification reports, providing insights into their performance in predicting heart disease.

## Conclusion

This project combines data analysis and machine learning to address the critical issue of heart disease prediction. By following the steps outlined in this repository, you can gain insights into the dataset, select the most relevant features, and create predictive models that aid in early detection and intervention for heart disease.

https://colab.research.google.com/drive/14kQALrOgZHshAROmGcOnW1k4rDTfoZW5#scrollTo=8-tE3OOjMpVF

