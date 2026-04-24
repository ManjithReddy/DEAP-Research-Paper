# DEP-Research-Paper
Analysis of Student Performance Using Educational Data
Analysis of Student Performance Using Educational Data
Description

This project focuses on analyzing student performance using educational datasets and machine learning techniques. The objective is to identify patterns in student data and predict academic outcomes based on various factors such as study time, attendance, and engagement. The project uses datasets like the UCI Student Performance dataset and the Open University Learning Analytics Dataset to build predictive models.

Objectives

The main objective of this project is to analyze student data and predict whether a student will pass or fail. It also aims to identify the key factors that influence student performance and compare different machine learning models to determine which performs best.

Methodology

The project follows a structured data analysis pipeline. First, the datasets are collected and explored. Then, preprocessing is performed which includes handling missing values, encoding categorical variables, and normalizing numerical features. Feature selection and feature engineering techniques are applied to improve model performance. Multiple machine learning models such as Logistic Regression, Support Vector Machine, Random Forest, and XGBoost are trained on the processed data. Hyperparameter tuning is performed using grid search with cross-validation. Finally, the models are evaluated using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

Dataset

This project uses two datasets. The UCI Student Performance dataset contains information about students’ academic performance along with demographic and social features. The Open University Learning Analytics Dataset contains large-scale data including student demographics and online learning activity. These datasets provide a comprehensive view of student behavior and performance. The details of these datasets are described in the research paper included in this repository .

Results

The results show that machine learning models can effectively predict student performance. Tree-based models such as Random Forest and XGBoost performed better compared to linear models like Logistic Regression. Important features identified include study time, absences, and engagement metrics. The findings suggest that student behavior and study habits play a significant role in academic success.

Technologies Used

This project is implemented using Python. Libraries such as Pandas are used for data manipulation, NumPy for numerical operations, Scikit-learn for machine learning models, and Matplotlib or Seaborn for data visualization.

How to Run

Clone the repository and install the required dependencies using pip. After that, run the main Python file to execute the project. Ensure that the dataset files are placed in the correct directory before running the code.

Project Structure

The project contains folders for data, source code, and outputs. The data folder includes datasets used for analysis. The source folder contains Python scripts for preprocessing, model training, and evaluation. The output folder contains results such as graphs, metrics, and visualizations.

Conclusion

This project demonstrates how educational data can be used to predict student performance and identify key factors affecting academic outcomes. The results highlight the effectiveness of machine learning in the field of education and provide insights that can be used for improving student success.
