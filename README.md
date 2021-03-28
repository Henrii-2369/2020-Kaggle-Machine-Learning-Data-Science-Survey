# 2020-Kaggle-Machine-Learning-Data-Science-Survey
submission for 2020 Kaggle Machine Learning &amp; Data Science Survey

The dataset provided (Kaggle_survey_2020_responses.csv) contains the survey results provided by Kaggle.
The survey results from 20036 participants are shown in 355 columns, representing survey questions. Not
all questions are answered by each participant, and responses contain various data types. In the dataset,
column Q24 “What is your current yearly compensation (approximate $USD)?” contains the ordinary
categorical target variable. The original data (kaggle_survey_2020_responses.csv) has been transformed
to clean_kaggle_data_2020.csv as per the code given in KaggleSalary_DataSet.ipynb. In the dataset to
be used for Assignment 2 (clean_kaggle_data_2020.csv- File to be read in notebook for this Assignment,
You should work with the clean dataset for this assignment), rows with the null values of salaries have
been dropped. In addition, two columns (‘Q24_Encoded’ and ‘Q24_buckets’) has been added at the end.
Column ‘Q24_buckets’ (Target Variable for Assignment 2) have been obtained by combining some salary
buckets in the column ‘Q24’. Column ‘Q24_Encoded’ has been obtained by label encoding the column
‘Q24_buckets’.
The purpose of this assignment is to train, validate, and tune multi-class ordinary classification models that
can classify, given a set of survey responses by a data scientist, what a survey respondent’s current yearly
compensation bucket is.
