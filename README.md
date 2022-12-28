# Prosper Loan Data Exploration

Prosper Marketplace was founded in 2005 as the first peer-to-peer lending marketplace in the United States. Since then, Prosper has facilitated more than 21 billion USD in loans to over 1.3 milliom people. Borrowers apply online for a fixed-rate, fixed-term loan between 2000 USD and 40000 USD. Individuals and institutions can invest in the loans and earn attractive returns. Prosper handles all loan servicing on behalf of the matched borrowers and investors. <p>In this project, I take a deep dive into Prosper Loans' data, curate questions neccessary for exploring and understanding how Prosper Loans have performed over time and factors that determine the Annual Percentage Rate (APR), and create visualizations to answer these questions, and to aid better communication and understanding of key insights gleaned from the data. <p> The data set used to complete this project contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others

### The structure of Prosper dataset:

> The dataset includes 113,937 loans in the dataset with 81 features. Most variables are numeric (floats) with many features containing mostly missing data.

### Main feature(s) of interest in the dataset:

> As a Sales Performance Analyst, I'm mainly interested in uncovering variables that drives Prosper's growth and identify areas of business opportunities. Linking certain variables to low and high performance will enable management develop strategies to improve business operations

### Features in the dataset that will help support investigation into feature(s) of interest:

> To aid my ivestigation of the main features of interest in the dataset, I consider the following variables important:
- Term: The duration of the Loan (in months).
- LoanStatus: The status of the loan (whether completed, past due, ongoing, or defaulted).
- BorrowerAPR: The Borrower's Annual Percentage Rate (APR) for the loan.
- BorrowerRate: Borrower's Interest Rate on the loan.
- BorrowerState: The state where the borrower lives.
- EstimatedLoss: Estimated Principal loss.
- ProsperScore: Customer Risk Score
- ListingCategory: The category of the listing that the borrower selected when posting their listing: 0 - Not Available, 1 - Debt Consolidation, 2 - Home Improvement, 3 - Business, 4 - Personal Loan, 5 - Student Use, 6 - Auto, 7- Other, 8 - Baby&Adoption, 9 - Boat, 10 - Cosmetic Procedure, 11 - Engagement Ring, 12 - Green Loans, 13 - Household Expenses, 14 - Large Purchases, 15 - Medical/Dental, 16 - Motorcycle, 17 - RV, 18 - Taxes, 19 - Vacation, 20 - Wedding Loans
- BorrowerState: The state where the borrower resides.
- Occupation: Borrower's occupation
- EmploymentStatus: Employment status, when listing was created.
- EmploymentStatusDuration: The length in months of the employment status at the time the listing was created.
- IsBorrowerHomeowner: Whether the borrower owns a home or not.
- DebtToIncomeRatio: The debt to income ratio of the borrower at the time the credit profile was pulled. This value is Null if the debt to income ratio is not available. This value is capped at 10.01 (any debt to income ratio larger than 1000% will be returned as 1001%).
- StatedMonthlyIncome: The monthly income of the borrower stated at the time the loan was issued.
- OriginalLoanAmount: The amount of the loan disbursed.
- MonthlyPayment: The monthly installment amount.
- LoanOriginationDate: The date at which the loan was issued.
