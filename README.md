# Guild-Forecasting-Modeling-Project

The goal of this project was given 3 hours take the given file and use SQL code necessary to pull the information from the database and then using Python, predict how likely a course is to be passed. With the extreemly limited time I choose to use a Catboost model becuase of the following paramters
1. Highly categorical data set
2. High cardinality of many data features 
3. Limited data set size 
    - Catboost there is a special modification for small data sets to prevent overfitting
4. Limited time to work on model trying to stay within the approximate 3 hour time limit. Extensive feature engineering would be required for other model types 

Model performance
- Accuracy: 79.6%
- Precision: 82.4%
- Recall: 93.4%

The model has a favors Recall in overall performance so it favors an instance where we consider that the cost of a false negative as high or when we consider predicting failure of a course when in reality the student would pass as very detrimental

Additional information about the dataset and model can be found in the extinsive code notes and slides. 
