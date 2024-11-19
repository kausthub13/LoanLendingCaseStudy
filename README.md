# Loan Lending Case Study
> As part of the consumer finance company who has the largest online marketplace for lending all types of loan. When a loan application is applied online, we have to identify if the person is going to be a default or a normal user. This is useful in reducing credit loss for the company and maximising the profits.
> 
> The objective is to understand all the different attributes that can be used to identify if the person is going to be normal loan user or a defaulter.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Analysis Types](#analysis-approach)
* [Conclusions](#conclusions)

## General Information
- This project is python based project on exploratory data analysis
- As part of the consumer finance company responsible for lending data to applicants, the role is to identify which customers can become defaulters and to deny similar applications to reduce credit loss
- The problem is to reduce the credit loss to the company by identifying key features which can help identify applicants who are risky
- Loan Lending dataset is being used which consists of data from 2007-2011 of the people who have applied for a loan and whether these people are currently paying the loan, paid off the loan or defaulted the loan


## Technologies Used
- matplotlib==3.9.2
- numpy==1.26.5
- pandas==2.2.2
- seaborn==0.13.2

## Analysis Approach
- Data cleaning
- Univariate Analysis
- Segmented Univariate Analysis

## Conclusions
- People with a weaker grade (C,D,E,F,G) of loan are more likely to default on the loans.
- People with weaker subgrades (C5,D5,E5,F5,G5) are more likely to default on the loans
- People with higher interest rates are more likely to default on loans
- Even if the income is verified, there is likelyhood of the person defaulting on loans
- As term value increases the chances of the person defaulting increases
