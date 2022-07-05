# Lending Club Case Study
In this case study, we are going to analyze the lending company’s past loan data and advise the company to minimize the credit loss and loss of business. We are going to analyze the attributes which are contributing to defaulting the loan. We will follow the required EDA steps to achieve our aim.
 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Working for a consumer finance company which specializes in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
1) If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
2) If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

The data given to us contains information about past loan applicants and whether they ‘defaulted’ or not.
The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study

Company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilize this knowledge for its portfolio and risk assessment.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
## Technologies Used
- Numpy Vesrion: 1.20.3
- Pandas Vesrion: 1.3.4
- Matplotlib Version: 3.4.3
- Seaborn Vesrion: 0.11.2

## Conclusions
Below are the recommendations of our analysis
- Higher the loan amount, rate of interest and installments in all income rage will leads to high probability of defaults
- More the DTI, the applicants are riskier
- All the loan applications must be verified
- Lower grade applicants has more probability of default. Especially, B and C grade needs to be considered for more verifications
- Home Improvement loan, Small Business loans and Debit Consolidation loan has more probability of defaults. Hence, recommend to reduce focus on these purpose loans or investigate more before approving.
- Reduce the number of terms
- Recommend to monitor the client’s revolving utilization rate
- Investigate more before approving the loan for applicants having more derogatory public records
- Reduce the loan amount or number of applications approved for the applicants with home ownership type Rent and Mortgage



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->




<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This case study was given as an assignment by upGrad for our PG program. Thanks for their guidance to complete this assignment.


## Contact
Created by [@munirathinamd] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
