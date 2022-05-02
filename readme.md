# Loan Data Exploration
## by (Andrew Samy Hanna)


## Dataset

This dataset containing 113,937 loans with 81 variables on each
loan, including loan amount, borrower rate (or interest rate),
current loan status, borrower income, and many others.

Data wrangling steps:-
- Data structure overview
- Selecting features of interest
- Remove duplicates and null values
- Exploration



## Summary of Findings

- Most of loans are taken by employed.
- Employment Duration is inversely proportional with the number of loans.
- The distribution of APR has a large peak around 0.2, then a smaller one around 0.28. 
  Also, there is a very high number of loans (more than 7000) with APR between 0.34 and 0.36.
- Most of the Loan Amounts are multiples of 5000: ( 5000 - 10000 - 15000 - 20000 - 25000 )
- Most loans length were 36 months long.
- The distribution of Monthly Loan Payment has a large peak around 250, then a smaller one around 500, then a verry small peak around 850.
  Also, there is a very high number of loans (more than 11000) with Monthly Loan Payment between 170 and 180.
- Most of loans are taken by the borrowers with monthly income around 5000
- The ProsperScore of most of the loans is between 4 and 8. 
- ProsperScore is directly proportional with: LoanOriginalAmount - AvailableBankcardCredit and inversely proportional with: BorrowerAPR
- Available Bank card Credit is inversely proportional with the number of loans
- More than 90% of loans without any Recommendations.
- Employed persons: has the largest LoanOriginalAmount
- Not-employed persons: has the largest BorrowerAPR
- The differences in MonthlyLoanPayment are relatively small
- Full time jobs have the greatest ProsperScore
- The differences in AvailableBankcardCredit are relatively small, although there are many extreme values
- 12-month LoanOriginalAmount nearly the same for all EmploymentStatus
- number of months is directly proportional with LoanOriginalAmount for all EmploymentStatus
- BorrowerAPR is directly proportional with EmploymentStatus for any number of months
- ProsperScore is directly proportional with: LoanOriginalAmount - AvailableBankcardCredit and inversely proportional with: BorrowerAPR
- Number of months is directly proportional with: LoanOriginalAmount - AvailableBankcardCredit - MonthlyLoanPayment and inversely proportional with: BorrowerAPR


## Key Insights for Presentation

> The lowest BorrowerAPR is with best (EmploymentStatus), high  (LoanOriginalAmount - AvailableBankcardCredit) and low (ProsperScore) 

> The best ProsperScore is with high  (LoanOriginalAmount - AvailableBankcardCredit) and low (BorrowerAPR) .