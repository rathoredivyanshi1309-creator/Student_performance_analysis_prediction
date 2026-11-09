Student Performance Analysis and Prediction System

1. Project Overview

The Student Performance Analysis and Prediction System is a minor project developed using Python and Machine Learning. The main aim of this project is to analyse students' academic performance and predict their final mathematics grades based on selected academic and personal factors.

The project uses data analysis and Linear Regression to understand the relationship between different student-related factors and their final grades.

2. Objectives

The main objectives of this project are:

- To analyse students' academic performance using a dataset.
- To identify factors that may influence students' final grades.
- To perform data cleaning and exploratory data analysis.
- To develop a Machine Learning model for grade prediction.
- To evaluate the performance of the model using standard evaluation metrics.

3. Dataset Description

The project uses the Student Performance Dataset obtained from the UCI Machine Learning Repository.

- Dataset: Student Performance (Mathematics)
- Number of Records: 395
- Number of Attributes: 33
- Target Variable: G3 (Final Mathematics Grade)

The selected features include:

- Study Time
- Previous Failures
- Absences
- First Period Grade (G1)
- Second Period Grade (G2)
- Age

Original Dataset Source:
https://archive.ics.uci.edu/dataset/320/student+performance

4. Tools and Technologies Used

The following tools and Python libraries were used:

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

5. Data Preprocessing

The dataset was examined and prepared before model development. The preprocessing steps included:

- Checking for missing values.
- Checking and removing duplicate records.
- Selecting relevant features for prediction.
- Preparing the data for model training and testing.

The cleaned dataset was also saved as a separate CSV file.

6. Exploratory Data Analysis

Exploratory Data Analysis (EDA) was performed to understand the distribution and relationships within the dataset.

The following visualisations were created:

- Histogram
- Bar Chart
- Scatter Plot
- Box Plot
- Correlation Heatmap

These visualisations helped in understanding student grades and the relationship between the selected features.

7. Machine Learning Model

Linear Regression was used as the main Machine Learning algorithm to predict students' final mathematics grades.

The dataset was divided into training and testing sets using an 80:20 ratio. The model was trained using the selected features, and its predictions were compared with the actual grades.

Ridge Regression was also explored through hyperparameter tuning for comparison.

8. Model Evaluation

The Linear Regression model was evaluated using the following metrics:

Evaluation Metric| Result
Mean Absolute Error (MAE)| 1.33
Root Mean Squared Error (RMSE)| 2.11
R-squared (R²)| 0.782

Five-fold cross-validation was also performed, giving a mean R² score of 0.819.

Ridge Regression was tested through hyperparameter tuning. Although it achieved a higher cross-validation score during tuning, its test-set R² score did not improve over Linear Regression.

9. Results and Findings

The model was able to identify relationships between the selected academic factors and students' final mathematics grades.

The evaluation results indicate that the Linear Regression model performed reasonably well on the test dataset. The project also demonstrates how data analysis and Machine Learning can be used to study academic performance.

10. Limitations

- The project uses only the mathematics dataset.
- The predictions are based on the selected features.
- Student performance may depend on several other factors that are not included in the dataset.
- The model provides estimates and cannot guarantee exact future grades.

11. Installation and Execution

Requirements

Python 3.x is required to run the project.

Install Required Libraries

Run the following command:

pip install -r requirements.txt

Running the Project

1. Download or clone this repository.
2. Open "Student_Performance_Analysis.ipynb" in Google Colab or Jupyter Notebook.
3. Upload the original "student-mat.csv" dataset if it is not already available in the notebook environment.
4. Run the notebook cells in sequence.
5. View the data analysis, visualisations, model predictions and evaluation results.

12. Repository Contents

The repository includes:

- Python Jupyter Notebook containing the project source code.
- Original Student Performance dataset.
- Cleaned dataset.
- Data visualisation graphs.
- Saved Linear Regression model.
- Model feature information.
- Project report in PDF format.
- "requirements.txt" containing the required Python libraries.

13. Conclusion

This project provided practical experience in data preprocessing, exploratory data analysis and Machine Learning. It helped in understanding how academic data can be analysed and used to predict student performance.

The project also provided an opportunity to work with Python libraries and evaluate a predictive model using different performance metrics.

14. Author

Name: Divyanshi Rathore
Project: Student Performance Analysis and Prediction System
Program: AI/ML with Python Training Program
Batch: September 2026
