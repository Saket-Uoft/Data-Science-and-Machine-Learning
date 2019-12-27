# Project Course-Introduction to Data Science and Analytics
## Salary Classification of Data Scientists Community Based upon a survey conducted by Kaggle

### Background:
The dataset provided (mutiplechoiceResponses.csv) contains the survey results provided by Kaggle. The
survey results from 23860 participants are shown in 395 columns, representing survey questions. Not all
questions are answered by each participant, and responses contain various data types.
In the dataset for this project , column Q9 “What is your current yearly compensation (approximate
$USD)?” contains the ordinary categorical target variable. Rows with null values or undisclosed salaries
have been dropped. 

The purpose of this project is to
1) understand and explore employment in the data science community, as represented in a survey
conducted by Kaggle.
2) train, validate, and tune multi-class ordinary classification problem that can classify, given a set of survey
responses by a data scientist, what a survey respondent’s current yearly compensation bucket is.

### This project Follows a certain storytelling path which is according to the order mentioned below-

### 1-Data Cleaning-
For the data cleaning step, handle missing values however you see fit and justify your approach.
Provide some insight on why you think the values are missing and how your approach might impact
the overall analysis. Suggestions include filling the missing values with a certain value (e.g. mode
for categorical data) and completely removing the features with missing values. Secondly, convert
categorical data into numerical data by encoding and explain why you used this particular encoding
method. 

### 2-EDA-
Present 3 graphical figures that represent trends in the data. How could these trends be used to
help with the task of predicting yearly compensation or understanding the data? All graphs
should be readable and presented in the notebook. All axes must be appropriately labelled.
b. Visualize the order of feature importance. Some possible methods include correlation plot, or
a similar method. Given the data, which of the  original attributes in the data are most related to
a survey respondent’s yearly compensation?

### 3-Feature Selection-
Explain how feature engineering is a useful tool in machine learning. Then select the features to
be used for analysis either manually or through some feature selection algorithm (e.g. regularized
regression). 

### 4-Model Implementation-
Implement logistic regression algorithm on the training data using 10-fold cross-validation. How
does your model accuracy compare across the folds? What is average and variance of accuracy for
folds? Treating each value of hyperparameter(s) as a new model, which model performed best?
Give the reason based on bias-variance trade-off. An output of your algorithm should be a
probability of belonging to each of the salary buckets. Apply scaling/normalization of features, if
necessary

### 5-Model Tuning-
Improve the performance of the models from the previous step with hyperparameter tuning and
select a final optimal model using grid search based on a metric (or metrics) that you choose.
Choosing an optimal model for a given task (comparing multiple classifiers on a specific domain)
requires selecting performance measure

### 6-Testing and Discussion-
Use your optimal model to make classifications on the test set. How does your model perform on
the test set vs. the training set? The overall fit of the model, how to increase the accuracy (test,
training)? Is it overfitting or underfitting? Why? Plot the distribution.


