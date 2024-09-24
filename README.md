# Project Name

 * This project aims to perform an Exploratory Data Analysis (EDA) on a given dataset of past loan applicants which have paid or defaulted on their loan. 
 * The EDA process involves cleaning and analysing the  dataset, 
 *  cleaning involaves preparing the data for analysis. such as its distribution, missing values, outliers, and relationships between variables. 
 *  The goal is to gain insights and understanding of the data using it to taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This jupyter notebook contains an Exploratory Data Analysis of a dataset of loan applicants. THe EDA process involves cleaning up the data and performing univarite and bivariate analysis on it. The analysis is done using different types of plots offered by seaborn and matplotlib. Once plotting is done we draw insights from the graphs.
- If the applicant is not likely to repay the loan, then approving the loan may lead to a financial loss for the company. The busines objective is  understand the driving factors (or driver variables) behind loan default.This will help take action like deny the loan application or reduce loan amount. The company can utilise this knowledge for its portfolio and risk assessment. 

- Dataset used: Lending Club Case Study. (loan.csv)

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Borrowers in grades B, C, and D, particularly in sub-grades 4 and 5, appear to be at higher risk of defaulting.
- Most borrowers fall into the 10-15 and 5-10 years of credit history range. Borrowers with less experience handling credit i.e 0-15 years are more likely to default than seasoned borrowoeres i.e 30-40 years of experience.
- Interest rate increases as grade decreases. The median interest rate of defaulted loans is slightly greater in high grade loans and it is significantly greater in lower grade loans. A low grade high interest loan is very likely to default.
- Higher Loan Amounts Lead to Higher Charge-Off Rate

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python==3.12.2
- pandas==2.2.1
- matplotlib==3.9.2
- matplotlib-inline==0.1.7
- numpy==1.26.4
- seaborn==0.13.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was part of Exploratory Data Analysis module for PG Diploma in Machine Learning and Artificial Intelligence offered by IIIT Bangalore and Upgrade.



## Contact
Created by [@pranjal-verma] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->