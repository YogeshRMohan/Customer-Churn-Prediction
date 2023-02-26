# Customer-Churn-Prediction

# Objective

To predict customer churn based on various factors in a telecom industry using a telecom industry dataset. This prediction would help the company understand if the customer would churn or not based on the customer behavior and take necessary actions for long term customer retention.

# Data Preprocessing

Step-1: Categorical variables are converted to type str.

Step-2: Checked for missing values and imputed valued with median. 

Step-3: Dummy variables are created for categorical variables.

Step-4: Checked for correlation among predictors and removed correlated features.

Step-5: Min-Max scaling done for numerical variables.

#Train-Test Split

Step-6: Data is divided into train (70%) and validation (30%) sets. Synthetic minority over sampling technique is performed as the data is imbalanced with less churned observations.

# Modeling

Step-7: With hyperparameter tuning the following models were built: Logistic regression, Random Forest, Decision Tree, Support Vector Machine

# Evaluation and Prediction

Step-8: Because of a focus on reducing false-negative(saying customers will not churn out when it is not the case), false positive spiked. As a business analyst, my goal is to predict customers who would churn so the focus on reducing false-negatives.

Support Vector Machine performed best in terms of lower false negatives and higher recall. 
