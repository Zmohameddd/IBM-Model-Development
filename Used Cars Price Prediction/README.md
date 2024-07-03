# Used Cars Prediction 
Predicting Used Car Prices

## Key Concepts

## 1. Simple Linear Regression

In simple linear regression, we use a single feature (in this case, "highway-mpg") to predict the response variable, which is the "price" of the used car. The goal is to find a linear function that best fits the relationship between the predictor and the response.

## 2. Multiple Linear Regression

Sometimes, a single feature may not be enough to accurately predict the price. In multiple linear regression, we use multiple features (like "horsepower", "curb-weight", "engine-size", and "highway-mpg") to predict the "price". This allows us to capture more complex relationships in the data.

## 3. Polynomial Regression

Linear models may not always be the best fit for the data. Polynomial regression is a technique that allows us to model non-linear relationships by introducing higher-order terms of the predictor variables.

## Model Evaluation

To determine the effectiveness of our models, we'll use the following metrics:

### 1. R-squared (R²)

R-squared is a statistical measure that represents the proportion of the variance in the dependent variable (price) that is predictable from the independent variable(s). It ranges from 0 to 1, and a higher value indicates a better fit.

### 2. Mean Squared Error (MSE)

MSE is the average of the squared differences between the predicted values and the actual values. It measures the overall magnitude of the errors in the same units as the dependent variable. A lower MSE indicates a better model fit.

### 3. Root Mean Squared Error (RMSE)

RMSE is the square root of the MSE, and it provides an interpretable measure of the average magnitude of the errors in the same units as the dependent variable.

## Notebook Structure

The notebook is divided into the following sections:

Setup: We'll start by importing the necessary libraries and loading the dataset.
### Linear Regression and Multiple Linear Regression: 
Here, we'll develop a simple linear regression model using "highway-mpg" as the predictor variable and a multiple linear regression model using multiple features.
Model Evaluation Using Visualization: We'll visualize the performance of the models using regression plots and residual plots.
### Polynomial Regression and Pipelines:
We'll explore the use of polynomial regression to improve the model's fit and demonstrate the use of data pipelines.
Measures for In-Sample Evaluation: We'll calculate the R-squared, MSE, and RMSE for the different models to quantify their performance.
### Prediction and Decision Making: 
Finally, we'll use the trained models to make predictions and discuss the process of determining the best model fit.
## Key Takeaways

* The multiple linear regression model performed the best, with an R-squared of 0.809 and an MSE of 1.20e+07.
The polynomial regression model also showed improvement over the simple linear regression model, with an R-squared of 0.674 and an MSE of 2.05e+07.

* When determining the best model fit, we should consider both the R-squared and the MSE/RMSE. Generally, a higher R-squared and a lower MSE/RMSE indicate a better model fit.
Conclusion
