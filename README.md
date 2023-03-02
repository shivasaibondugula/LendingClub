# Lending club
> Using Exploratory Data Analysis (EDA) for basic understanding the risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'.The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment.
- For this project, we are using the data provided - [data set](loan/loan.csv).

## Conclusions
- The applicants who has charged off has high average int_rate than those who are fully paid.
- the applicants who has charged off has high average loan_amount than those who are fully paid.
- The applicants who has charged off has low average annual_inc than those who are fully paid.
- For purposes like debt_consolidation,home_improvement,house,medical - If the int_rate is more, they applicants are likely to be charged off.
- As the years pass, applicants who have high int_rate are likely to be charged off and the rate is increasing.
- For grade G, If the loan amount is high, the applicant is likely to be charged off.
- More percentage of applicants whose annual income in range 1-30000 are likely to be be charged off.
- The charged off percentage of applicants whose int_rate is above 14 is more compare to those whose int_rate is less than 14 and it is very high for applicants whose interest rate is in range 17-23.
- The charged off percent is high for the applicants whose loan amount more than 15000 and is even more if loan amount is more than 25000.
- The applicants whose the percentage of installment on monthly income is more are likely to be Charged Off.


## Technologies Used
- Python - version 3.9.13
- Pandas - version 1.4.4
- Numpy - version 1.21.5
- Matplotlib - version 3.5.2
- Seaborn - version 0.11.2

## Acknowledgements
- This project is developed as part of the Exploratory Data Analysis course required for Executive Post Graduate Diploma in Machine Learning and AI from IIIT Bangalore.


## Contact
Created by shivasaibondugula4@gmail.com - feel free to contact me!
