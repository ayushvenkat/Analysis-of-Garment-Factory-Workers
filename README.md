# Analysis-of-Garment-Factory-Workers

This project uses the following dataset from the UCI repository: https://archive.ics.uci.edu/ml/datasets/Productivity+Prediction+of+Garment+Employees 
This dataset has a column called productivity which is a continuous variable. We predict this from all the other columns in two ways:  
(1) By treating productivity as a continuous variable (i.e. as it is) and using Decision Trees, KNN and Polynomial Regression.  
(2) By dividing it into two classes which are reasonably balanced, and then using Bayes classifiers and Logistic Regression.  
(3) We also only had data for 3 months, so we used time series to predict productivity of future months.
