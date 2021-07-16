# Loan Data from Prosper
## by Ali Shaker


## Dataset

> This data set contains 113,937 loans with 81 variables on each
loan, including loan amount, borrower rate (or interest rate),
current loan status, borrower income, and many others.

> I worked on only 14 features from 81 because they are so many features

> The data set was contain NULL values and I dropped all rowes that contain NULL values


## Summary of Findings

> > most loan statues are current statues then the completed statues then the chargedoff then the others

> The number of Borrowers who are Homes owners is sligtly more than the number of Borrower who are not Homes owners

> Most borrowers take the loan for Debt Consolidation

> There is no one who is 'Not employed' take a loan (All the Borrowers are Employed)

> Most Borrowers have an income range 50000 - 74999 $

> most loans have number of investors that funded the loan between 0 and 100 investors

> The most borrowers rate is 0.15

> most of percent funded is about 1 (100%)

> There are many APR from 4% to 46% but the most of them are about 20%

> Most of borrowers have a Monthly Income about 5000 USD

> Loan Original Amount started from 1000 to 35000 and there are multiple peaks observed at 4000 , 10000 and 15000 $.

> The beggist APR is for those whose income range from 1 - 24999 USD and the lowest APR is for those whose income range more than 100000 USD (The Lower income range the more APR) (The more income range the lower APR)

> There is a correlation between the LoanOriginalAmount and the BorrowerAPR that the more LoanOriginalAmount the less of BorrowerAPR

> There is a correlation between the MonthlyLoanPayment and the BorrowerAPR that the less MonthlyLoanPayment the more of BorrowerAPR

> The borrowers who are home owners have a higher BorrowerRate than who is not a home owner¶

> The term (36 monthes) have a biggest APR for all of borrowers who have an income range less than 100000 USD


## Key Insights for Presentation

> What affects the borrower’s APR or interest rate?

## Resources

> https://www.digitalcitizen.life/command-prompt-how-use-basic-commands

> https://github.com/shravankoninti/Udacity_DataAnalyst/blob/master/Project_5_Visualization/Exploratory_visualization.ipynb

> https://stackoverflow.com/questions/13413590/how-to-drop-rows-of-pandas-dataframe-whose-value-in-a-certain-column-is-nan

> https://www.crazyegg.com/blog/understanding-using-heatmaps-studies/
