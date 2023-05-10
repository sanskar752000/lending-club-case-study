# Project Name
> This is Exploratory Data Analysis done on the data from Lending Club company which offers variety of loans to their customers.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- <b>About the case study:</b> Lending Club is a peer-to-peer lending platform that connects borrowers with investors. The company was founded in 2007 and has since facilitated over $50 billion in loans.In this presentation, we will analyze the data provided by Lending Club to identify the types of borrowers who are most likely to default on their loans.
- <b>Business Problem that need to be solved:</b> Lending Club company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

    Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 
    If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

    In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 
- <b>Dataset used:</b> The dataset that is being used for this have 39717 records and 111 features. The record present is from year 2007 till 2011.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Lending Club should source verify the annual income of the borrower. Loan should not be approved or if approved should be very less in amount for non-verified borrowers.
- They should not grant higher amount of loan to the people who have 0 or near to 0 experience.
- They should charge higher interest rate or reduce the amount of loan or prevent giving loans to lower grade borrower such as E, F, and G.
- If the loan is taken for the purpose of small business or debt consolidation higher interest should be charged or limit the amount of loan available to these types of borrower.
- DTI should be measured more closely before approving the loan. We found in the analysis that after DTI of 20 chances of loans default gets high.
- They should limit the amount or increase the interest rate whenever in any year there is financial crisis happening and this decision should be maintain for upto 2-3 years.
- hey should reduce the loans taken with higher interest for 60 months, because these are likely to get default.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- IDE - Anaconda Jupyter Notebook
- language - python v3.9
- library - pandas v1.4.4
- library - numpy v1.21.5
- library - matplotlib v3.5.2
- library - seaborn v0.11.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was a case study provided by Upgrad
- References taken for this case study are:
    1. https://stackoverflow.com/
    2. https://www.kaggle.com/
    3. https://www.google.com/
    4. https://www.lendingclub.com/company/about-us


## Contact
Created by [https://github.com/sanskar752000/ & https://github.com/Mahimaawasthy/] - feel free to contact me!
