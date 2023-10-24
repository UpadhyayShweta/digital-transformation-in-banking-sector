# Classification Algorithms for Digital Transformation

## Introduction 

Bank XYZ has a growing customer base where the majority of them are liability customers (depositors) vs. borrowers (asset customers). The bank is interested in expanding the borrower’s base rapidly to bring in more business via loan interests.

A campaign that the bank ran in the last quarter showed an average single-digit conversion rate. In the last town hall, the marketing head mentioned that digital transformation is the core strength of the business strategy, how to devise effective campaigns with better target marketing to increase the conversion ratio to double-digit with the same budget as per the last campaign.

**Our aim is to develop a machine learning model to identify potential borrowers to support focused marketing.**

## Objective 

Build a ML model to predicting the potential customers who will convert from liability customers to asset customers to perform focused digital marketing.

### Approach

- Understanding the dataset
- Exploratory Data Analysis (EDA) –
  - Data Visualization
- Feature Engineering
  - Dropping of unwanted columns
  - Removal of null values
  - Checking for multi-collinearity and removal of highly correlated features
- Model Building (using different classification algorithms)
  - Performing train test split
  - Logistic Regression Model
  - Weighted Logistic Regression Model
  - Naive Bayes Model
  - Support Vector Machine Model
  - Decision Tree Classifier
  - Random Forest Classifier
- Model Validation
  - Accuracy score
  - Confusion matrix
  - Area Under Curve (AUC)
  - Recall score
  - Precision score
  - F1-score
- Handling the unbalanced data using imblearn.
- Hyperparameter Tuning (GridSearchCV)
  - For Support Vector Machine Model
- Creating the final model and making predictions
- Save the model with the highest accuracy in the form of a pickle file.


### Tech stack

Language - Python
Libraries – numpy, pandas, matplotlib, seaborn, sklearn, pickle, imblearn

