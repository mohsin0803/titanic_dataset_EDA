# Titanic Dataset - Exploratory Data Analysis (EDA)

This repository contains a Python-based Exploratory Data Analysis (EDA) of the Titanic dataset. The Titanic dataset is widely used for classification problems, where the goal is to predict whether a passenger survived or not based on various features such as age, gender, passenger class, and more.

## Contents

1. **titanic-dataset.csv** - The Titanic dataset in CSV format.
2. **EDA Notebook** - A Jupyter notebook (`EDA_Titanic.ipynb`) that contains the full exploratory analysis and visualizations for the Titanic dataset.
3. **README.md** - This file describing the repository and its contents.

## Files Breakdown

- **EDA_Titanic.ipynb**: This Jupyter notebook includes the following analyses:
    - **Data Loading**: Load the dataset from a CSV file.
    - **Basic Information**: Display the shape of the dataset, column information, and summary statistics.
    - **Null Value Analysis**: Check for missing values and visualize them using heatmaps.
    - **Survival Distribution**: Visualize the distribution of survivors and non-survivors using pie charts.
    - **Passenger Class Distribution**: Plot the distribution of passengers across different classes using pie charts.
    - **Age Distribution by Gender**: Create a histogram of passenger ages, separated by gender.
    - **Sibling/Spouse Analysis**: Visualize the distribution of passengers based on the number of siblings/spouses aboard.
    - **Parent/Children Analysis**: Visualize the distribution of passengers based on the number of parents/children aboard.
    - **Survival Based on Family Size**: Analyze how family size affects survival rates.
    - **Correlation Heatmap**: Generate a heatmap of the correlation between numerical variables in the dataset.

## Prerequisites

Make sure to install the following Python libraries before running the notebook:

- **Pandas**: Data manipulation and analysis.
- **NumPy**: Support for large, multi-dimensional arrays and matrices.
- **Matplotlib**: Plotting library for creating static, animated, and interactive visualizations.
- **Seaborn**: Statistical data visualization built on top of Matplotlib.
- **Jupyter**: Interactive notebooks for creating and sharing documents with live code, equations, visualizations, and narrative text.

You can install the required libraries via `pip`:

```bash
pip install pandas numpy matplotlib seaborn jupyter
