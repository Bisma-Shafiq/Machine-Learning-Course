## Project Overview
This project develops a linear regression model to predict the salary package a student might receive based on their CGPA. By analyzing the relationship between CGPA (Cumulative Grade Point Average) and salary package, this model can help students and educational institutions understand how academic performance may impact job offers.

## Data Description
The dataset used in this project contains the following columns:

1- cgpa: The student’s cumulative GPA, representing their academic performance.

2- package: The salary package offered to the student (in appropriate units, e.g., thousands of dollars).
## Project Workflow

1- Exploratory Data Analysis (EDA):Visualizations, such as scatter plots, are used to analyze the relationship between CGPA and salary packages. This helps in understanding if a linear relationship exists.

2- Feature Selection:cgpa is used as the independent variable (feature), and package is the dependent variable (target).

3-Data Splitting:The data is split into training and testing sets. Typically, an 80-20 split is used, where 80% of the data is used for training the model, and 20% is used for evaluating its performance.

4- Model Training:A simple linear regression model is trained using the cgpa as the predictor for package.
The model learns the relationship, calculating the best-fit line through the data by minimizing the error between predicted and actual packages.

5- Model Evaluation:After training, the model is tested on the testing set to evaluate its performance. Key metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared score are used to assess accuracy.

6- Model Interpretation:Model coefficients (slope and intercept) are extracted to understand the relationship. The slope indicates how much the package changes for each unit increase in CGPA, while the intercept shows the base package when CGPA is zero.

7- Visualization of Results:The linear regression line is plotted over the data points to visually confirm how well the model fits the data.

## Dependencies
pandas for data handling and manipulation.
numpy for numerical operations.
matplotlib and seaborn for data visualization.
sklearn for building and evaluating the regression model.
## Result
The model provides a direct estimate of the expected salary package based on CGPA, giving users insight into the impact of academic performance on job offers. By visualizing the linear relationship, it helps in determining how improvements in CGPA could potentially enhance job opportunities and packages.