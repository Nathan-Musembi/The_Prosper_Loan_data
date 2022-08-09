# (Exploration Of The Prosper Loan Dataset)
## by (Nathan Musembi)


## Dataset
 The  Prosper Loan  dataset contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. See this [data dictionary](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0) to understand the dataset's variables.

## Summary of Findings
>In the Univariate Exploration, we investigated the distribution of the  features listed below and observed the following:

- BorrowerAPR rates is approximately normal with the peak between 15 and 25. Additionally there is an increase in the number of loans for borrower rates around 29 and 35 percent.
- The Borrower annual interest rate appear to be moderately skewed to the right with a peak between 14 and 16. Additionally there is an increase in the number of loans for annual interest rates around 32%.
- Lender Yield is nomarlly distributed with most of the values between 10% and 20% and we also notice that there is a spike at 30%
- The ProsperRating (Alpha) also appears to be normally distributed. 
- The ProsperRating (numeric) is normally distributed with the peak at 'C' (4.0). 
- Prosper score is normally distributed with the peak being at 4.0, 6.0 and 8.0 scores.
- LoanOriginalAmount shows that the distribution of Original Loan Amounts is skewed to the right. The mostly borrowed amount is between 4k and 5k inclusive.
- Credit grade  distribution is normal with the peak at CreditGrade C.
- It is observed that most of the loan borrowers are from California (CA) followed by Texas (TX), Newyork (NY) and Florida (FL).
- The pie chart above shows that 60% of the loan borrowers have employment status as 'Employed'.
- It is observed that most of the loan borrowers have an income range of 25,000 - 49,999 dollars (32192 loan borrowers) followed by 50,000 - 74,999 dollars (31050 loan borrowers).
- Most prefered loan repayment term is 36 months (3 years), with 77% of the loan borrowers
- The histogram plot of AmountDelinquent is skewed to the right. We therefore consider transforming the xscale to a log scale of measurement.
- It is observed that the Stated Monthly Income is skewed to the right. We therefore consider transforming the xscale to a log scale. 


> Bivariate exploration has revealed that there is a :
 - Positive correlation between BorrowerAPR and BorrowerRate.
 - Positive correlation between BorrowerAPR and LenderYeld.
 - Positive correlation between Borrower rate and LenderYeld .
 - Negative correlation between ProsperScore and BorrowerRate.
 - Negative correlation between ProsperScore and BorrowerAPR.
 - Negative correlation between ProsperScore and LenderYeld.
 - Negative correlation between the BorrowerAPR and LoanOriginalAmount.
> Employed people have lower Inter-Quartile Range than those who are not employed.
> Current and completed loans have lower rate than the past-due loans and have lower mean.


## Key Insights for Presentation
> From the Univariate  analysis of the Prosper Loan dataset we conclude that the distribution of BorrowerAPR, BorrowerRate, ProsperRating (Alpha), The ProsperRating (numeric), ProsperScore and CreditGrade is normal. The histogram plots of LoanOriginalAmount , AmountDelinquent and StatedMonthlyIncome is skewed to the right but after a  log scale transformation it becomes normal.

> The Bivariate analysis revealed that BorrowerAPR vs BorrowerRate, BorrowerAPR vs LenderYeld and Borrower rate vs LenderYeld are positively correlated whereas, ProsperScore vs BorrowerRate, ProsperScore vs BorrowerAPR, ProsperScore vs LenderYeld and BorrowerAPR vs LoanOriginalAmount are negatively correlated.

> Further we can conclude that Employed people are diverse regarding the Loan Status and BorrowerAPR as they have sometimes high borrower rate and that they have lower BorrowerAPR across all loan status categories.# The_Prosper_Loan_data
