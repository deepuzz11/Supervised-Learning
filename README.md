# Student Scores Prediction using Linear Regression

## Overview
This project aims to predict student scores based on the number of study hours using linear regression. It explores the relationship between study hours and scores through exploratory data analysis (EDA) and builds a predictive model to estimate scores.

## Dataset
The dataset used in this project is "student_scores.csv", which contains two columns: "Hours" (number of study hours) and "Scores" (student scores).

## Requirements
To run the code, you need the following Python libraries:
- pandas
- matplotlib
- seaborn
- scikit-learn

You can install these libraries using pip: 
pip install pandas matplotlib seaborn scikit-learn

## Usage
1. Clone this repository: git clone https://github.com/your-username/student-scores-prediction.git
2. Navigate to the project directory: cd student-scores-prediction
3. Run the Python script: python 1.py


This will execute the code and display various visualizations and predictions based on the dataset.

## Description
- **Data Loading**: Load the dataset using pandas and display the first few rows to understand its structure.
- **Summary Statistics**: Compute summary statistics (mean, median, min, max) for study hours and scores.
- **Data Visualization**: Visualize the distribution of study hours and scores using histograms.
- **Correlation Analysis**: Calculate the correlation coefficient between study hours and scores.
- **Pairplot**: Visualize pairwise relationships between study hours and scores using a pairplot.
- **Model Building**: Split the data into training and testing sets, and train a linear regression model.
- **Prediction**: Predict the score for a given number of study hours (9.25 hours/day).
- **Residual Analysis**: Perform residual analysis to evaluate the model's performance.

## Conclusion
This project demonstrates how to perform exploratory data analysis (EDA) and build a predictive model using linear regression for student scores prediction based on study hours.


