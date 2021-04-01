# House-Sale-Price-Prediction-using-Regression-Algorithm
![image](https://user-images.githubusercontent.com/66888595/113287494-4a92f380-930b-11eb-90c7-21042975a155.png)


## Table of Contents :
* Overview
* Motivation
* Technical Aspects
  * EDA and Data Preprocessing
  * Implementation of Regression Algorithm
* To Do
* Technology Used
* Team
* Credit

## Overview
To predict a regression problem, like *house sale price prediction*, some regression algorithms are used to predict the best result. The model `./price_pred_model.pkl` takes a previous processed and scaled data set and predict the sale price of the house. This model can predict 85% accurately the rate of a house.

## Motivation
It's usually a big to predict or evalute the price of a house depending on some features manually. For this, using a proper machine learning algorithm, we can do this in no time. 

## Technical Aspects
* **EDA and Preprocess of the dataset**
> In this notebook file, the data insights, trends are explored using `matplotlib`, `pandas`, `numpy`. Missing values and outliers have been treated. Using feature generation and transformation techniques, new effective features were added and unnecessary features were excluded.

* **Implementation of *Regression Model* on the dataset**
> In this section, <br> i. The dataset was splitted into X(Observation Matrix) and y(Target Vector)<br>ii. Removal of *Multicollinearity* using the value of *Variation Inflation Factor*.<br>iii.Splitting into `X_train`, `y_train`, `X_test`, `y_test`(training and test dataset).<br>iv.Implementation of `sklearn.linear_model.LinearRegression()` and checking for *R2_score*, *Homoscedasticity* and *distribution of error*.<br>v.Checking for importance of various feature given by the model.<br>Implementation of `sklearn.linear_model.Lasso()` and `sklearn.tree.DecisionTreeRegressor` and the plot of the tree and the linear relation between the target values and the predicted values.

## To Do
i. Implement a pipeline in this problem statement.<br>
ii. Increament of the accuracy of the model :arrow_upper_right: .<br>
iii. Deployment.<br>

## Technology Used 
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try)

## Team
[Manojit Roy](https://www.linkedin.com/in/manojit-roy-8a93a1183/)

## Credit
This dataset is provided by Internshala Machine Learning Training.
