# credit-risk-classification

# Objective

Import and convert the lending_data.csv file and ti the data into a Logistic Regression Model and analyze how well it will predict a healthy loan and a high risk loan. 

# Methods
* Split the data into training and testing datasets setting y from the loan-status column and x from the reamining columns.
* Create a Logistic Regression Model and fit the data to the model. Evaluate the model's performance by generating a confusion matrix and classification report.
* Create a oversampler model by importing RandomOverSample
* Fit the data to the new model and review results

  # Findings
  * The Logist Regression model predicts the health loan with 100% precision and 99% recall. The high-risk loans are not predicted as well with a 85% precision and 91% recall.
  * The Logist Regression model fit to the oversampled data, predicts the health loan with 100% precision and 99% recall. The high-risk loans are not predicted as well with a 85% precision and 91% recall
