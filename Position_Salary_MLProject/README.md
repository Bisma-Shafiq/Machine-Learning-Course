# Polynomial Regression for Position Salary Prediction
This project demonstrates the use of polynomial regression to predict salaries based on job levels. Polynomial regression is ideal here as it captures the non-linear relationship between job level and salary, which linear regression might not accurately represent.

# Project Overview
The goal of this project is to predict salaries for various job levels using polynomial regression. The process includes data preprocessing, training, and evaluating the model, followed by visualizing the results to understand the model's performance.

# Key Steps:
### Data Preprocessing:

We begin by loading the dataset and checking for any missing values.
Perform descriptive statistics to understand the data distribution.
### Polynomial Transformation:

A polynomial transformation is applied to the feature (job level) to enable the model to capture non-linear patterns.
### Model Training:

A linear regression model is trained on the transformed data, allowing it to learn the relationship between job level and salary.
### Model Evaluation:

The model's accuracy is evaluated using R-squared on test data, which helps measure how well the model generalizes.
### Prediction and Visualization:

We visualize the model's predictions against actual salaries, creating an intuitive understanding of how well it captures the underlying pattern.
The model is then used to make salary predictions for specific job levels.
# Results
The model's R-squared score provides insight into its accuracy on the test data, indicating how closely the predicted values align with the actual salaries.

# Conclusion
This project demonstrates how polynomial regression is effective for modeling non-linear relationships in data, such as predicting salaries based on job level. The model successfully captures the trends in the data, allowing for accurate predictions at different job levels.

