# Student Performance Data Analysis

## Project Overview

This project analyzes student academic performance using Python.
The objective is to explore factors that influence final grades and build a simple predictive model.

## Dataset

The dataset contains information about students including:

* Gender
* Age
* Study time
* Past failures
* Absences
* Grades (G1, G2, G3)

Source: UCI Machine Learning Repository

## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Exploratory Data Analysis

Several visualizations were created to understand the dataset:

* Grade distribution
* Gender vs performance
* Study time vs grades
* Absences vs grades
* Correlation heatmap

## Machine Learning Model

A Linear Regression model was trained to predict the final grade (G3) using features such as:

* G1 (first period grade)
* G2 (second period grade)
* Study time
* Failures
* Absences

The model was evaluated using Mean Absolute Error.

## Key Insights

* Previous grades strongly predict final grade.
* Students with higher study time perform better.
* Past failures negatively affect performance.
* Higher absences often correspond to lower grades.

## Project Structure

student-performance-analysis
│
├── data
│   └── student-mat.csv
│
├── notebooks
│   └── eda_student_performance.ipynb
│
└── README.md

## Author

Kartikeya Pandey
