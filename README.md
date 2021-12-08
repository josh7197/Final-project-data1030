# Insurance cross-selling prediction

# The goal of the project
A goal of this project is predicting whether health insurance holders are interested in car
insurance plans that the same company offers. Rather than marketing for unspecified potential
customers, cross marketing tactics for the target customers are less costly and more monetarily
efficient. The prediction model would allow the company to implement the improved sales
strategy with less capitals and higher number of vehicle insurance holders.

# The model
The analytical model for the goal is a classification because the target variable is a dummy
variable, “Response”, with 1 or 0 if an insurance holder is interested in a vehicle insurance is 1
or 0. The data set has 12 features, including the target variable and ID, and 381,109 rows(data
points). However, ID does not explain whether someone is interested in the insurance plan,
therefore, I would better omit this variable in the model. Therefore, the dataset consists of 10
explanatory variables and a single target variable with 381,109 data points.

# Used package version
- Python version is 3.9.7 
- numpy version 1.21.1  
- matplotlib version 3.4.2 
- sklearn version 0.24.2
- pandas version 1.3.1 
- xgboost version 1.3.3
- shap version 0.39.0 
