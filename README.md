# UK-Housing Price Analysis
## INTRODUCTION 
This publication presents a comprehensive analysis of housing prices using regularized linear regression. 
The study aims to explore the factors that significantly influence housing prices and develop a predictive model to estimate property values accurately. 
By leveraging regularization techniques, we address the challenges of multicollinearity and overfitting in the dataset. 
The findings of this research contribute to a deeper understanding of the housing market dynamics and provide valuable insights for both buyers and sellers.

## PACKAGES REQUIRED
* Numpy-1.23.1
* Pandas-2.8.2
* scikit-learn-3.1.0
* scipy-1.25.0
* seaborn-1.16.0

## ACTIONS INVOLVED
+ Utilization of hybrid combination of RFE and manual methods for feature selection.
+ Finding optimal regularization parameters for the methods involved using Grid Search using K-Fold cross validation.
+ Constructing linear regression model with ridge and lasso regularization for predicting 'AveragePrice' (component of dataset determining the selling price of property).
+ Employing R-Squared scores on the testing set to evaluate our model.
+ Resolve which model to proceed with.

