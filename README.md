
# PredictingEmployeeAttrition
Employee attrition can have a significant impact on an organization's effectiveness and growth. This project aims to predict employee attrition rates using machine learning techniques.The findings of the project can provide valuable insights for organizations to optimize their employee retention strategies, ultimately reducing employee attrition rates and improving overall workforce stability.

# Data Description
•	Dataset Link - IBM HR Analytics Employee Attrition & Performance

•	Size of the data: 1470 observations

•	Variable Count: 35

•	Dependent Variable: Attrition(16% attrition)

•	Independent Variables: 34 (7 Categorical Variables,10 Ordinal Variables & 17 Numeric Variables)

# Approach
In this project, I have developed a Machine Learning Model to predict the Employee Attrition by implementing various Machine Learning Algorithms such as Random Forest, Logistic Regression, and Support Vector Machine. Conducted exploratory data analysis using various data visualization techniques.

The major hurdle was that there were 1233 observations of Non-Attrition (Stay) and only 237 observations of Attrition (leave), resulting in highly imbalanced data. To deal with the imbalanced data, I used SMOTE (Synthetic Minority Oversampling Technique). Since the data contained many categorical variables with different values and numerical variables of varying scales, I used one-hot encoding for the categorical variables and MinMaxScaler to normalize the numerical variables to the same scale.For Model Evaluation,I used Confusion Matrix,Accuracy,Recall & Roc-Auc.

Achieved good accuracy on the 'IBM HR Analytics Employee Attrition & Performance' dataset from Kaggle,using Logistic Regression.
