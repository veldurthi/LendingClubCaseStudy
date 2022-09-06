# Lending Club Case Study
> Lending loans to ‘risky’ applicants is the largest source of financial loss
(called credit loss). The credit loss is the amount of money lost by the lender 
when the borrower refusesto pay or runs away with the money owed.  

The main objective is to be able to identify these risky loan applicants, 
then such loans can be reduced thereby cutting down the amount of credit loss. 
Identification of such applicants using EDA is the aim of this case study.   

Perform an analysis to understand the driving factors (or driver variables)
behind loan default, i.e.the variables which are strong indicators of default.  
The company can utilise this knowledge for its portfolio and risk assessment. 



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
As a part of a Consumer Lending Finance Company, which specialises in lending various types of loans, we need to identify the patterns which indicates if a loan is likely to Default. When the company receives a loan application, it has to make a decision for loan approval based on applicant's profile. This decisioning is associated with 2 kinds of risks;

a. If the applicant is likely to pay the loan, not approving such loan will result in loss for the company;
b. If the applicant is likely to default the loan, approving such loan application will also result in loss.

The data given below contains the information about past loan applicants and whether they ‘defaulted’ or not. We need to perform EDA to understand how consumer attributes and loan attributes infulence the decisioning. In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment.



## Conclusions

### Single Variant Driving Factors for Default:
Applicants having house_ownership as 'RENT'
Applicants who use the loan to clear other debts
Applicants who receive interest at the rate of 13-17%
Applicants who have an income of range 31201 - 58402
Applicants who have 20-37 open_acc
Applicants with employement length of 10
When funded amount by investor is between 5000-10000
Loan amount is between 5429 - 10357
Dti is between 12-18
When monthly installments are between 145-274
Term of 36 months
When the loan status is Not verified
When the no of enquiries in last 6 months is 0
When the number of derogatory public records is 0
When the purpose is 'debt_consolidation'
Grade is 'B'
And a total grade of 'B5' level.


### Bivariant Driving factors for Defaulter: 
Applicants taking loan for 'home improvement' and have income of 60k -70k
Applicants whose home ownership is 'MORTGAGE and have income of 60-70k
Applicants who receive interest at the rate of 21-24% and have an income of 70k-80k
Applicants who have taken a loan in the range 30k - 35k and are charged interest rate of 15-17.5 %
Applicants who have taken a loan for small business and the loan amount is greater than 14k
Applicants whose home ownership is 'MORTGAGE and have loan of 14-16k
When grade is F and loan amount is between 15k-20k
When employment length is 10yrs and loan amount is 12k-14k
When the loan is verified and loan amount is above 16k
For grade G and interest rate above 20%


## Technologies Used
1. pandas
2. numpy
3. matplotlib
4. seaborn
5. datetime



## Acknowledgements
Sunil Veldurthi | github - @gitmydshub


## Contact
- Sunil Kumar Veldurthi
- Alexander Krishna


