# Loan approval analysis of Lending Club
> Lending club is an online platform which connect borrower of loan with investors. There is already one screening is done
>by this platform and when the application comes to investor then he should clearly know which loan application
> Should be approved or rejected. This project is to identify the criteria of loan applicants, for whome loan should be approved by invetstor.Also when it should be rejected.This will also give insight of data for each importatnt variable

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
#Overview
- The lending club lends money to borrower when it receives a loan application
- The Company needs to make decision based on user's profile.
- There are two type of risk:
    - The User may pay
    - The User may not pay
- We need to Analyse variables from given the dataset and find the driving variable to make right decision on weather to approve the loan application or not.
.#Background
 Lending club is an online platform which connect borrower of loan with investors. There is already one screening is done
by this platform and when the application comes to investor then he should clearly know which loan application Should be approved or rejected.
## Business Problem to be solved
This project is to identify the criteria of loan applicants, for whome loan should be approved by invetstor.Also when it should be rejected.On the basis of analysed data, those factors should be considered while approving or rejcting loan.
### Dataset
There are 3 types of data sets used here:
    1) df_noncurrent - Full cleaned up data set
    2) df_full_paid - Data set for the borrowers who fully paid the loan
    3) df_charged_off -  Data set for the borrowers who did not pay the loan


## Conclusions
1.  Strong correlation between funded_amnt and funded_amnt_inv
2.  Negative correlation between dti and annual inc, that means if there is higher income then debt to income will be less and also these candidates will be paying loan
3.  Funded amount by investor is directly proportion with Funded amount by lending club, hence one of the columns can be removed.
4.  If annual income is less then 58000 - 60000 then there is more probability of having defaulter
5.  If Loan amount greater then 10000/-, it is risky as it mostly may go into the bucket of defaulters.
Subgrade with G5 will be most likely default the loan.
6.  Maximum number of loans were taken and number of fully paid too is for debt_consolidation and credit_card bills. 
7.  Loan taken for small business are risky as they are maximum median for charged off data set.
8. Lowered interest rates will help to get paid off , in charged off data set more then 12% with 36 month is defaulter and for same duration if interest rate is between 10 – 12 % then loans are paid of more in Fully paid data set .
9.  Employees having more then 10 years of experience should be approved with loan below 12000 and will more tend to fully pay, however if loan more then 12000 is given then it may be charged off.
10. Charged Off numbers is low with all the verification status, and so is the fully paid number is high in all of the verification status. Hence this variable is not giving much insights.


## Technologies Used
- Python 3 is used with below libraries:
pandas 
numpy
pandas
numpy
matplotlib.pyplot 
seaborn 


## Acknowledgements
Give credit here.
- This project was inspired by Upgrad team for EDA analysis on lending club
- This project grading system was based on https://www.marlo.online/loan-grades.

## Contact
Created by [@githubusername] - feel free to contact me!

