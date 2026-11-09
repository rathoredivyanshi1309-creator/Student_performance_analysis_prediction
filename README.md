# Student_performance_analysis_prediction
Students performance analysis and final grade prediction using python, data visualization, and linear regression.
Student Performance Analysis and Prediction System

1. Introduction

This project focuses on analysing student academic performance and predicting final mathematics grades using Python and machine learning techniques.

The project uses the Student Performance Dataset obtained from the UCI Machine Learning Repository.

2. Objectives

- To analyse student academic performance.
- To identify patterns and relationships in the dataset.
- To perform Exploratory Data Analysis (EDA).
- To build a machine learning model for grade prediction.
- To evaluate the performance of the developed model.

3. Dataset Description

- Dataset: Student Performance (Mathematics)
- Source: UCI Machine Learning Repository
- Total Records: 395
- Total Attributes: 33
- Target Variable: G3 (Final Grade)

4. Features Selected

The following features were used:

- Study time
- Past failures
- Absences
- First-period grade (G1)
- Second-period grade (G2)
- Age

5. Tools and Technologies

- Python
- Google Colab
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Joblib

6. Project Methodology

1. Dataset collection and loading.
2. Data inspection and cleaning.
3. Exploratory Data Analysis.
4. Data visualisation.
5. Feature selection.
6. Train-test splitting.
7. Linear Regression model development.
8. Model evaluation.
9. Cross-validation and Ridge Regression comparison.
10. Model saving and reloading.

7. Exploratory Data Analysis

Five visualisations were created to understand the dataset:

- Histogram
- Bar Chart
- Scatter Plot
- Box Plot
- Correlation Heatmap

8. Model Performance

Linear Regression was used as the main prediction model.

Evaluation Metric| Result
MAE| 1.33
RMSE| 2.11
R² Score| 0.782

The model achieved a mean R² score of 0.819 through 5-fold cross-validation.

9. Model Tuning

Ridge Regression was also tested using GridSearchCV. The best alpha value was 0.01, with a cross-validation R² score of 0.834.

However, it did not improve the test-set R² score over Linear Regression.

10. Limitations

The model uses a limited number of selected features. Student performance can also depend on several personal, social and educational factors that are not fully represented in the dataset.

11. Conclusion

This project demonstrates how data analysis and machine learning can be used to study student academic performance and estimate final grades. The results show the usefulness of Linear Regression for this dataset.

12. Repository Contents

- "cleaned_student_data.csv" – Cleaned dataset
- PNG files – Data visualisation graphs
- "linear_regression_model.pkl" – Saved prediction model
- "model_features.pkl" – Saved feature information
- Project report – Detailed documentation

13. References

UCI Machine Learning Repository:

https://archive.ics.uci.edu/dataset/320/student+performance

Author

Divyanshi Rathore
