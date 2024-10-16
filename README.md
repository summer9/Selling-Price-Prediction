# Selling-Price-Prediction
This project involves using numerical methods in Python. Our team aimed to predict the selling price of specific products.

**Difficulties**

One of the main challenges was finding appropriate data. We found a dataset on Kaggle titled **Amazon Sales Dataset** and selected a product with varying prices - WHITE HANGING HEART T-LIGHT HOLDER. Initially, we aimed to find data on familiar products, but we did not have enough time to gather the specific data we wanted
Data on Kaggle: <[Amazone sales dataset](https://www.kaggle.com/code/mehakiftikhar/amazon-sales-dataset-eda/input)> 

**Math behinds Python method**
We used single and multiple linear regression for our predictions.
- Simple Linear Regression: Simple linear regression finds a linear relationship that describes the correlation between an independent and a dependent variable.
- Multiple Linear Regression: This extends linear regression to involve multiple independent variables.
  
**Evaluation Metrics**
- Mean Squared Error (MSE): MSE shows how close the predicted values are to the actual values. It is sensitive to outliers
- R² Score: The R² score explains how well the regression model fits the data. It is less sensitive to outliers than MSE. We can use the model for making predictions. 

**Compare 2 ways of calculation:**
- Case 1: Predicting Total Price (Unit Price × Quantity):Mean Squared Error (MSE): 935.55 ,R² Score: 0.9684
- Case 2: Predicting Unit Price:  Mean Squared Error (MSE): 2.294549977092901e-28, R² Score: 1.0 (perfect score)
  --> There is overfitting. The model memorized specific patterns,it does not change when we input new data -new features (even outliers)
  
**What can we improve for learning process?**
- Analyse other products to compare their behavior
- Add more features to the model
- Analyse which features can affect the price most:  evaluate the coefficients of the linear regression model
