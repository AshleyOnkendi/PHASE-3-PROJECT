# PHASE-3-PROJECT
## Telecommunication
# 1 BUSINESS UNDERSTANDING
## 1.1 Project overview
This project aim to build a model that will predict whether a customer is likely to leave SyriaTel soon
## 1.2 Business problem
SyriaTel, a telecommunication firm, is facing a significant issue of customer churn that may adversely affect its revenue and future. The firm should identify the customers who are likely to discontinue using their services and the reasons why they decide to do so. Through this learning, SyriaTel can implement measures to resolve customer problems and prevent them from leaving.
## 1.3 Project objectives
### 1.3.1 Main objective
This project forecasts SyriaTel customer churn by identifying those most likely to stop usage and determines the most significant drivers of churn. This will enable SyriaTel to take proactive measures to retain customers and prevent revenue loss.
### 1.3.2 Specific objectives
1. To identify customer behavour by analyzing day,night calls and their correlation to churn.
2. Analyze customer behavior, usage patterns, and service interactions to determine the main factors influencing churn.
3. To identify how the number of customer service interactions relates to the possibility of customer churn for your business.
4. Provide actionable insights that help SyriaTel implement targeted retention efforts, such as personalized offers or improved customer service.
# 2 DATA UNDERSTANDING
I engaged in the following activities
I started with importing libraries
Loaded the dataset
Checking rows and columns
Checking the data type
Checking for the statistics information
Checking the statistics information with transpose
# 3 DATA PREPARATION
## 3.0 Data cleaning
 I checked for the missing values
Duplicates 
Checked for unique values in the categorical values
Drop unnecessary column
confirm if the phone number has been removed
checking the outlier
identify numerical columns except area code
 Calculating upper Q3 (75th percentile) and lower Q1 (25th percentile) 
 Calculating interquartile range
# 4 EDA
1. Univariate analysis
2. Bivarite analysis
3. Multivariate analysis
## 5. MODELING
Models that will be used are
1. Logistic regression
2. Decision tree
### LOGISTIC REGRESSION WHEN THE CLASS IS IMBALANCED
 Preprocessing
It is the changing of categorical variable to numerical variable
 Splitting data into target and predictors
split the data into train, test and split¶
Scaling¶
 Build the model
 Predict Y
The accuracy¶
The accuracy was 88.59%
### LOGISTIC REGRESSION(WITH BALANCED CLASS)/SMOTE TECHNIQUE
Preprocessing
It is the changing of categorical variable to numerical variable
 Splitting data into target and predictors
split the data into train, test and split¶
Scaling¶
 Build the model
 Predict Y
The accuracy¶
The accuracy was 68%
### DECISION TREE(using hyperparameter)
Preprocessing
It is the changing of categorical variable to numerical variable
 Splitting data into target and predictors
split the data into train, test and split¶
Scaling¶
 Build the model
 Predict Y
The accuracy¶
The accuracy was 94%
### EVALUATION
Decision tree is the best model to use because it has an accuracy of 94% compared to logistic with an accuracy of 68%

