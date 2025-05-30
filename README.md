# Boston House Pricing Prediction

This project focuses on predicting Boston housing prices using statistical analysis and machine learning techniques in Python. 
## Objective
The primary objective of this project is to develop a predictive model that can estimate the median value of owner-occupied homes in the Boston metropolitan area based on various features.

## Dataset

The project utilizes the *Boston Housing Dataset*, which is a classic dataset in the field of machine learning and statistics. It contains information about housing values in suburbs of Boston, along with various demographic and socio-economic factors.

The dataset includes the following features:

* *CRIM:* Per capita crime rate by town
* *ZN:* Proportion of residential land zoned for lots over 25,000 sq.ft.
* *INDUS:* Proportion of non-retail business acres per town
* *CHAS:* Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
* *NOX:* Nitric oxides concentration (parts per 10 million)
* *RM:* Average number of rooms per dwelling
* *AGE:* Proportion of owner-occupied units built prior to 1940
* *DIS:* Weighted distances to five Boston employment centres
* *RAD:* Index of accessibility to radial highways
* *TAX:* Full-value property-tax rate per \$10,000
* *PTRATIO:* Pupil-teacher ratio by town
* *B:* $1000(Bk - 0.63)^2$ where Bk is the proportion of blacks by town
* *LSTAT:* Percentage lower status of the population
* *MEDV:* Median value of owner-occupied homes in \$1000's (*Target Variable*)

The dataset used is uploaded in the repository titled 'boston.csv'.

## Project Structure

The project typically follows these steps:

1.  *Data Exploration and Understanding:*
    * Loading the dataset using libraries like pandas.
    * Performing exploratory data analysis (EDA) to understand the characteristics of the data, including descriptive statistics, visualizations (histograms, scatter plots, box plots), and identifying potential outliers or missing values.
2.  *Data Preprocessing:*
    * Handling missing values (if any).
    * Feature scaling or normalization, if required by the chosen model.
    * Splitting the data into training and testing sets to evaluate the model's performance on unseen data.
3.  *Model Selection and Training:*
    * Choosing appropriate statistical models or machine learning algorithms for regression, such as:
        * Linear Regression
        * Polynomial Regression
        * Decision Trees
        * Random Forests
        * Gradient Boosting Regressors
    * Training the selected model(s) using the training data.
4.  *Model Evaluation:*
    * Evaluating the performance of the trained model(s) on the testing data using appropriate metrics for regression, such as:
        * Mean Squared Error (MSE)
        * Root Mean Squared Error (RMSE)
        * Mean Absolute Error (MAE)
        * R-squared (Coefficient of Determination)
5.  *Model Tuning (Optional):*
    * Optimizing the model's hyperparameters using techniques like GridSearchCV or RandomizedSearchCV to improve its performance.
6.  *Results and Conclusion:*
    * Summarizing the findings, discussing the performance of the chosen model(s), and drawing conclusions based on the results.

## Libraries Used

The project utilizes the following Python libraries:

* *pandas:* For data manipulation and analysis.
* *numpy:* For numerical computations.
* *scikit-learn (sklearn):* For accessing the dataset, data splitting, model implementation, and evaluation metrics.
* *matplotlib and seaborn:* For data visualization.
* *statsmodels:* For statistical modeling and analysis (potentially used for more traditional statistical approaches).

## Course Information  
This project was completed as part of the *Statistics for Data Science with Python* course on Coursera.
