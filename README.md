# Classifying-Shooting-Incident-Fatality-in-New-York-City
Problem statement : We have partnered with, a leading data analytics firm specializing in urban crime analysis, they have initiated a project to enhance response strategies through data-driven insights and efficient allocation of resources based on severity prioritization in New York City.

They aim is to provide actionable insights to law enforcement agencies for the development of targeted policing strategies. The task is to develop a machine learning model to analyze historical shooting incident data, classifying them as fatal or non-fatal. This model will provide valuable insights into the factors influencing fatality rates and the ability to focus on high priority areas. (Predict: STATISTICAL_MURDER_FLAG - TRUE or FALSE)

Overview :This project is dedicated to optimizing response strategies for the New York Police Department (NYPD) through advanced data-driven insights and efficient resource allocation. The goal is to classify historical shooting incidents as fatal or non-fatal, thereby enhancing the prioritization and effectiveness of response efforts.

Dataset Details

Objective: Classify shooting incidents into fatal or non-fatal categories.
Dataset Dimensions: 27,312 records with 21 features.
Data Preprocessing

Column Removal: Excluded non-essential columns such as 'OCCUR_DATE', 'OCCUR_TIME', 'BORO', 'LOC_OF_OCCUR_DESC', 'LOC_CLASSFCTN_DESC', 'LOCATION_DESC', 'PERP_AGE_GROUP', 'PERP_SEX', 'PERP_RACE', 'VIC_AGE_GROUP', 'VIC_SEX', 'VIC_RACE', and 'Lon_Lat'.
Encoding: Implemented label encoding to convert categorical variables into numerical format.

Outlier Detection: Applied Isolation Forest for outlier detection and removal to ensure data quality.

Class Imbalance: Addressed class imbalance using the Synthetic Minority Over-sampling Technique (SMOTE) to enhance the representation of minority classes.
Model Evaluation Seven machine learning algorithms were assessed to determine the optimal model for predicting shooting incident severity:

Logistic Regression

Decision Tree

Random Forest

Gradient Boosting

Support Vector Machine

Naive Bayes

K-Nearest Neighbors Results: The Random Forest Classifier demonstrated superior performance, achieving an accuracy of 74.50%.
Conclusion The Random Forest Classifier emerged as the most effective model for predicting shooting incident outcomes. This achievement is a result of rigorous data preprocessing, including the management of categorical features, handling missing values, and mitigating class imbalance.
