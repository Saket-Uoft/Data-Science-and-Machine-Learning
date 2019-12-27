# Salary prediction of Data Scientists based upon a survey
Background:
Kaggle has hosted an open data scientist competition in 2018 titled “2018 Kaggle ML & DS Survey
Challenge.” The purpose of this challenge was to “tell a data story about a subset of the data science
community represented in this survey, through a combination of both narrative text and data
exploration.” More information on the competition, data, and prizes can be found on:
https://www.kaggle.com/kaggle/kaggle-survey-2018
The dataset provided (mutiplechoiceResponses.csv) contains the survey results provided by Kaggle. The
survey results from 23860 participants are shown in 395 columns, representing survey questions. Not all
questions are answered by each participant, and responses contain various data types.
In the dataset for Assignment 1, column Q9 “What is your current yearly compensation (approximate
$USD)?” contains the ordinary categorical target variable. Rows with null values or undisclosed salaries
have been dropped. In addition to the column “Q9” containing the target variable, an index column
“index” has been added. (Please refer to Kaggle_Salary.csv and the manipulation process can be found in
SalaryKaggle-DataSet.ipynb)
The purpose of this assignment is to
1) understand and explore employment in the data science community, as represented in a survey
conducted by Kaggle.
2) train, validate, and tune multi-class ordinary classification problem that can classify, given a set of survey
responses by a data scientist, what a survey respondent’s current yearly compensation bucket is.
