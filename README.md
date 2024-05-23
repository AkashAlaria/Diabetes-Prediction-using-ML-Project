# Diabetes Prediction using Machine Learning

This project aims to predict whether a person has diabetes or not based on various medical features using machine learning algorithms. The dataset used in this project is originally from the National Institute of Diabetes and Digestive and Kidney Diseases.

## Dataset

The dataset consists of several medical predictor variables and one target variable, Outcome, indicating whether a person has diabetes (1) or not (0). The features in the dataset are:

- Pregnancies: Number of times pregnant
- Glucose: Plasma glucose concentration
- BloodPressure: Diastolic blood pressure (mm Hg)
- SkinThickness: Triceps skin fold thickness (mm)
- Insulin: 2-Hour serum insulin (mu U/ml)
- BMI: Body mass index (weight in kg/(height in m)^2)
- DiabetesPedigreeFunction: Likelihood of diabetes based on family history
- Age: Age (years)
- Outcome: Class variable (0 or 1)

## Dependencies

The following Python libraries are required to run the code:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Usage

1. Clone the repository or download the source code.
2. Make sure you have the required dependencies installed.
3. Prepare the dataset and ensure it is in the correct format.
4. Run the Python script to preprocess the data, train the machine learning models, and evaluate their performance.

## Contents

The repository contains the following files:

- `Diabetes Prediction using Machine Learning.ipynb`: The Jupyter Notebook containing the code for data preprocessing, exploratory data analysis, model training, and evaluation.
- `README.md`: This file, providing an overview of the project and instructions for usage.

## Methodology

The project follows these steps:

1. Import required libraries
2. Load the dataset
3. Perform exploratory data analysis (EDA)
4. Clean the data (handle missing values, outliers, etc.)
5. Visualize the data
6. Feature selection
7. Split the data into training and testing sets
8. Build and train classification algorithms (Logistic Regression, Naive Bayes)
9. Evaluate the models using performance metrics (accuracy, confusion matrix, precision, recall, F1-score)

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
