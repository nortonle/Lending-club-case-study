# Lending-club-case-study
Given a dataset of a lending club containing data from 2007 to 2011, we need to analyse to find bad debt customers patterns. These patterns may help to prevent bad debt for new to bank customers in future. In the scope of analysis, we can only focus on some descriptive statistics analysis to determine patterns. Although we apply univariate analysis on some variables, it's not really univariate. Because we always combine them with loan status.

After analysis, we detect some indicators that may be helpful for future use (if we need to build predictive analysis for this case study).

## Table of Contents
- Data prepartion and cleansing
- Univariate analysis
- Bivariate analysis
- Deriving new metrics


## Conclusions
There are severals helpful indicators that may help to prevent lending out money to high potential deliquency customers.

1. Year of employment
    * By right, the longer years of experience prove the higher credit trust. In this case study customers, who are with more than 8 years of experience, tend to less pay off the loans.
2. Loan purpose
    * Small business, educational, renewable energy are three purposes that need to handle with care.
    * Especially, combing loan purpose with home ownership status, we have another stronger indicators showing that customers, who own a home, apply for loans to study or to invest in small business tend to less pay the loans compared to others.
3. Debt to income
    * Another surprised indicators is debt to income. Usually, the higher debt to income ratio prove the abilities to pay back the loans. In this case study we find out that the higher the ratio, the higher the percentage of charged off.

Once a loan is disbursed to a customers, two additional indicators should be taken into consideration:
1. Number of installment
    * When customers reach to installment 10th to 15th, additional collection operations should be performed to make sure all loans are recovered.
2. Percent of principal received
    * This is not a very strong indicator, but it's no harm to additionally monitor. Similarity, when 10-20% principal are collection, we should involve more operations to monitor and ensure more principal are collected.
   
## Technologies and Python packages Used
- Python v3
- Pandas
- Numpy
- Matplotlib
- Seaborn

## Contact
Group project facilator:
- Le Nguyen Duc - norton0704@yahoo.co.uk
Group project member:
- Tran Chi Thao - Thaotc.pte@gmail.com
