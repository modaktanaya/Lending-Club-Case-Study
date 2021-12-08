# Lending Club Case Study
> Performing EDA on loan data to find the driver variables that indicates if the customer is likely to default or not.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
Lending Club is place facilitating different kinds of loans for different purposes. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.
We have the data from Lending Club about past loan applicants and whether they 'defaulted' or not.
The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.


## Conclusions
- Higher income decreases defaulter ratio.
- Higher interest rates increases defaulter ratio.
- When we go from category A-G, the defaulter ratio increases and also the interest rates are high for categories D, E, F and G.
- Higher the number of terms, higher the defaulter ratio.
- High and very high installments tend to have higher defaulter ratio.
- Category A and B have low interest rates as well as low defaulter ratio, so more loans can accepted for that applicants.
- High income is also a feature of customers that pays loans, so more loans can be accepted for customers with high income.
- Unsecured Purposes like small business and medical loans tend to be charged off.
- More number of derogatory public records and inquiries for last 6 months can increase the chances of being defaulter.


## Technologies Used
- pandas library
- numpy library
- matplotlib library
- seaborn library

## Acknowledgements
Give credit here.
- This project is developed as part of Exploratory Data Analysis module, Master of Machine Learning and AI, IIIT-Bangalore.


## Contact
Created by [@modaktanaya] - feel free to contact me!
