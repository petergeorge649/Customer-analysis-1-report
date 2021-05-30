# Customer-analysis-report

![alt text](https://github.com/petergeorge649/Customer-analysis-EDA/blob/main/png/analysis-customer-experience-france-belgium-europe-1.jpeg)

Image source: IntoTheMinds

## **Contents**
 
**[Project Otuline](project-otuline)**

**[Customer analysis 1](#customer-analysis-1)**

**[Customer analysis 2](#customer-analysis-2)**

**[Customer analysis 3](#customer-analysis-3)**

**[Customer analysis 4](#customer-analysis-4)**

## Project Otuline

![alt text](https://github.com/petergeorge649/Customer-analysis-EDA/blob/main/png/work.png)

## Customer analysis 1

The process:

Case Study

Get data

Cleaning/Wrangling/EDA

Processing Data

Modeling

Validation

Reporting

## Abstract

The objective of this data is to understand customer demographics and buying behavior. Later , I used predictive analytics to analyze the most profitable customers and how they interact. After that, I took targeted actions to increase profitable customer response, retention, and growth.

For this case study, I gathered the data from 3 csv files that are provided by IronHack. I used that data and complete the data cleaning tasks as per instructions.

## Instructions

Read the three files into python as dataframes

Show the DataFrame's shape.

Standardize header names.

Rearrange the columns in the dataframe as needed

Concatenate the three dataframes

Which columns are numerical?

Which columns are categorical?

Understand the meaning of all columns

Perform the data cleaning operations mentioned so far in class

Delete the column education and the number of open complaints from the dataframe.

Correct the values in the column customer lifetime value. They are given as a percent, so multiply them by 100 and change dtype to numerical type.

Check for duplicate rows in the data and remove if any.

Filter out the data for customers who have an income of 0 or less.

## Customer analysis 2

Marketing_customer_analysis.csv data continuation.

Dealing with the data

Show the dataframe shape.

Standardize header names.

Which columns are numerical?

Which columns are categorical?

Check and deal with NaN values.

Datetime format - Extracted the months from the dataset and store in a separate column. Then filtered the data to show only the information for the first quarter , ie. January, February and March. 

Furthermore: I Put all the previously mentioned data transformations into a function.

# Customer analysis 3

Marketing_customer_analysis.csv file continuation.

EDA (Exploratory Data Analysis) - Complete the following tasks to explore the data:

Show DataFrame info.

Describe DataFrame.

Show a plot of the total number of responses.

Show a plot of the response rate by the sales channel.

Show a plot of the response rate by the total claim amount.

Show a plot of the response rate by income.

# Customer analysis 4

In the customer analysis 4 the continuous distributions (mainly normal distribution), linear regression and how multicollinearity can impact the model are covered. 

Get the data

Use the jupyter file from the last lab (Customer Analysis Round 3)

Check the data types of the columns. Get the numeric data into dataframe called numerical and categorical columns in a dataframe called categoricals. (You can use np.number and np.object to select the numerical data types and categorical data types respectively)

Now we will try to check the normality of the numerical variables visually

Used seaborn library to construct distribution plots for the numerical variables

Used Matplotlib to construct histograms

Do the distributions for different numerical variables look like a normal distribution

For the numerical variables, check the multicollinearity between the features. Please note that we will use the column total_claim_amount later as the target variable.

Drop one of the two features that show a high correlation between them (greater than 0.9). Write code for both the correlation matrix and for seaborn heatmap. If there is no pair of features that have a high correlation, then do not drop any features
