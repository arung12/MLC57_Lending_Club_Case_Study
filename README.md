# Project Name
> Lending Club Case Study

## Table of Contents
* [General Info](#general-information)
* [Approach](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)

## General Information
The Lending Club is a consumer finance company which provides loan to urban consumer. The company receives the application from the consumer, Company has to make decision whether to Approve/Reject the Request.

There are two types of Risk
 - If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
 - If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

Dataset containing previous loan application data was provided, Objective is perform the EDA on dataset to understand how consumer attributes and loan attributes influence the tendency of default.So the company can mitigate two type of risk mentioned above

## Approach
1. [Data Sourcing](#Data-Sourcing)
2. [Data Preparation](#Data-Preparation)
   - [Data Understanding](#Data-Understanding)
       - [Importing Required Libraries and Configuration](#Importing-Required-Libraries-and-Configuration)
       - [Loading csv from local](#Loading-csv-from-local)
       - [Understanding Structure of dataset](#Understanding-Structure-of-dataset)
   - [Dataset Quality Check](#Dataset-Quality-Check)
       - [Missing values on Columns](#Missing-values-on-Columns)
       - [Data Quality checks on rows](#Data-Quality-checks-on-rows)
       - [Outlier Check](#Outlier-Check)
   - [Data Cleaning and Manipulation](#Data-Cleaning-and-Manipulation)
       - [Missing value treatment for columns](#Missing-value-treatment-for-columns)
       - [Missing value treatment for Rows](#Missing-value-treatment-for-Rows)
       - [Dropping Constant and Unique Columns](#Dropping-Constant-and-Unique-Columns)
       - [Outlier-Treatment](#Outlier-Treatment)
       - [Dropping-irrelevant-columns](#Dropping-irrelevant-columns)
       - [Fix Incorrect Data Types](#Fix-Incorrect-Data-Types)
       - [Derived Metrics](#Derived-Metrics)
 3. [Analysis](#Analysis)
    - [Univariate Analysis](#Univariate-Analysis)
       - [univariate analysis on outcome](#univariate-analysis-on-outcome)
       - [Univarite analysis on categorical variables](#Univarite-analysis-on-categorical-variables)
       - [Univarite analysis on continuous variables](#Univarite-analysis-on-continuous-variables)
       - [Univariate analysis with binned columns](#Univarite-analysis-with-binned-columns)
    - [Segmented Univariate Analysis](#Segmented-Univariate-Analysis)
       - [Segmented univariate analysis on categorical variables by loan_status](#Segmented-univariate-analysis-on-continuous-variables-by-loan_status)
       - [Segmented univariate analysis on categorical variables by loan_status](#Segmented-univariate-analysis-on-continuous-variables-by-loan_status)
    - [BiVariate Analysis](#BiVariate-Analysis)
       - [Bivariate Analysis on Numerical Variables](#Bivariate-Analysis-on-Numerical-Variables)
       - [Rate of Default vs Categorical Variables](#Rate-of-Default-vs-Categorical-Variables)
       - [Bivariate Analysis Continuous vs Categorical variables](##Bivariate-Analysis-Continuous-vs-Categorical-variables)
    - [MutiVariate Analysis](#MutiVariate-Analysis)

## Conclusions
- EDA Conducted on Given Dataset
- Variables influcing outcome Identified
- Project Analysis finding documented in ppt and python notebook


## Technologies Used
- numpyy - version 1.5.3
- pandas - version 1.24.3
- seaborn - version 0.12.2
- matplotlib - version 3.7.1

## Contact
Created by [@arung12](https://github.com/arung12) - feel free to contact me!