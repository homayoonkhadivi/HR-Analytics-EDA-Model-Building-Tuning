![bigstock-Recruitment-Concept-Idea-Of-C-250362193](https://user-images.githubusercontent.com/57557590/108717210-3f8dbc00-7532-11eb-8085-91c52d8d3839.jpg)
# HR-Analytics-EDA-Model-Building-Tuning
### In this notebook, I want to analyze the Human Resource dataset. I will build different models and compare them with their gained accuracy.

# Data Understanding & Problem

### The datasets contains the following categories such as: satisfaction_level
* 1 last_evaluation
* 2 number_project
* 3 average_montly_hours
* 4 time_spend_company
* 5 Work_accident
* 6 left
* 7 promotion_last_5years
* 8 department
* 9 salary
### Problem:
We want to predict if the employee left the company or not. 1 means the employee will left the company

# This Notebook Contains:
* Data Underestanding
* Data Exploration
* Data Preparation
* Data Visualization
* Feature Engineering
* Build Machine Learning Models
* Machine Learning Models With Cross Validation
* Model Evaluation
* Hyperprameters Tuning

# Data Visualization
![Salary](https://user-images.githubusercontent.com/57557590/108720918-a57c4280-7536-11eb-9fd2-1950372d3a23.PNG)
### The relationship between the amount of salary and left the company:
![Salary   Left](https://user-images.githubusercontent.com/57557590/108720923-a6ad6f80-7536-11eb-8ed6-73537f261b8f.PNG)
### The correlation matrix between the different features and the target variable
### Accuracy with Cross Validation Technique:
![Accuracy with CV](https://user-images.githubusercontent.com/57557590/108730071-69e67600-7540-11eb-8293-97f79afb3160.PNG)
# Machine Learning Models With Parameter tuning
![Correlation](https://user-images.githubusercontent.com/57557590/108721400-33f0c400-7537-11eb-9364-9586ed6813f3.PNG)
### Feature Importance
![Feature Importance](https://user-images.githubusercontent.com/57557590/108723508-96e35a80-7539-11eb-82d4-16f06d5f4f24.PNG)
# Accuracy with all features:
![Accuracy with all features](https://user-images.githubusercontent.com/57557590/108726967-47069280-753d-11eb-8a60-8eb476511481.PNG)
# Accuracy with important features
![Accuracy with importance features](https://user-images.githubusercontent.com/57557590/108727517-ea57a780-753d-11eb-9f9c-265e670e330f.PNG)
# Machine Learning Models With Cross Validation
![Accuracy with CV](https://user-images.githubusercontent.com/57557590/108730071-69e67600-7540-11eb-8293-97f79afb3160.PNG)
# Machine Learning Models With Parameter tuning
![Accuracy with GridSearch Tuning](https://user-images.githubusercontent.com/57557590/108731995-6358fe00-7542-11eb-8522-1a1491914095.PNG)
# Final Results:
### Accuracy Comparision:
![Accuracy Comparision](https://user-images.githubusercontent.com/57557590/108746130-29dbbf00-7551-11eb-8b44-7267bef1c983.PNG)

# Conclusion Results coulde be described as below:
* Here we can compare the accuracy obtained by different Classification Models with different strategy
For A quick revision
* Accuracy with all features means the all features of data were used for prediction of will employee left or not? this accuracy is obtained on the test data which was not used in training.
* Accuracy with important features means the same as above but here only 5 most important features were used. The importance of features we got by using Random Forest Classifier.
* Accuracy with CV means the mean of accuracies which were obtained on iteration of one CV. here 10 iterations were used
* Accuracy with GridSearchCV means the best score obtained after tuning the model. Here for CV only 5 folds were used
123456789101123456789112345
