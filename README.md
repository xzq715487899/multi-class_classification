Background:

For this assignment, you are responsible for answering the questions below based on the dataset provided. You will then need to submit a 3-page report in which you present the results of your analysis. In your report, you should use visual forms to present your results. How you decide to present your results (i.e., with tables/plots/etc.) is up to you but your choice should make the results of your analysis clear and obvious. In your report, you will need to explain what you have used to arrive at the answer to the research question and why it was appropriate for the data/question. You must interpret your final results in the context of the dataset for your problem.

Background:


In this assignment, we will continue to work on the “2022 Kaggle Machine Learning & Data Science Survey” dataset.
The purpose of this challenge was to “tell a data story about a subset of the data science community represented in this survey, through a combination of both narrative text and data exploration.” More information on this competition can be found on: https://www.kaggle.com/competitions/kaggle-survey-2022


The dataset provided (kaggle_survey_2022_responses.csv) contains the survey results provided by Kaggle. The survey results from 23997 participants are shown in 296 columns, representing survey questions. Not all questions are answered by each participant, and responses contain various data types. In the dataset, column ‘Q29’ “What is your current yearly compensation (approximate $USD)?” contains the ordinary categorical target variable. The original data (kaggle_survey_2022_responses.csv) has been transformed to clean_kaggle_data_2022.csv as per the code given in KaggleSalary_DataSet.ipynb. In the dataset to be used for Assignment 2 (clean_kaggle_data_2022.csv – file to be read in notebook for this Assignment, You should work with the clean dataset for this assignment), rows with the null values of salaries have been dropped. In addition, two columns (‘Q29_Encoded’ and ‘Q29_buckets’) have been added at the end. Column ‘Q29_buckets’ (Target Variable for Assignment 2) has been obtained by combining some salary buckets in the column ‘Q29’. Column ‘Q29_Encoded’ has been obtained by label encoding the column ‘Q29_buckets’.


The purpose of this assignment is to train, validate, and tune multi-class ordinary classification models that can classify, given a set of survey responses by a data scientist, what a survey respondent’s current yearly compensation bucket is.
