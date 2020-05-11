# Predicting house prices using Linear Regression

The goal is to predict the median sale price for each city by property type for four months from Oct 2019 to Jan 2020. 
For each record in the test set, predicted the median sale price.

# Software and Libraries

This project uses the following software and Python libraries:

 Python
 NumPy
 pandas
 matplotlib
 scikit-learn

# Overview

 Workflow
 Preprocessing and transformation
 Statistic and visualization of the data
 Feature Selection and Model Selection 
 Best Model and Best Features
 Result
 Conclusion
 Prediction Results
 
 
 # Preprocessing and transformation
 
 Checked for missing values
 Removed comma in the target variable "Median Sale Price (in 000's of dollars)“
 Converting Date variable which is object to Pandas compatible datetime datatype
 Convert categorical variable(city and property type) into dummy/indicator variables.

# Conclusion

Increased accuracy by adding polynomial regression of degree 3 and regularising the model with Ridge regularisation.  
By using the model,  predicted the median sale price for each city by property type for four months from Oct 2019 to Jan 2020. 
According to the test dataset, 90% of the predictions for home prices can be explained by the model. The model predicts the Median Home Prices in with an error of +/- 1.1% of the actual prices.
