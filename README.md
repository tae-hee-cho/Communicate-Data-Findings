# Effects of Loan Characterics on Borrower's APR
## by Tae-Hee CHo

## Dataset

The Dataset contains 113,917 loans, each loan has information on each borrower's annual percentage rate (APR), status, borrowed amount, debt, etc. Variables with missing values were dropped to make the Dataset more accurate. This investigation will be analyzing factors that could influence borrower's APR and what loans were taken by what type of borrowers.

The dataset can be download here: https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1547358770029000


## Summary of Findings

After analyzing each variables. creditscore were found to be negatively correlated to Borrower's APR. orrower' Scores (given from 0 to 11) gave the strongest negative relationship with borrower's APR.

Borrowers with different statuses were also analyzed. It came out that borrowers that have loan records in the past tended to receive lower APR percentage, and borrower with real estate holdings and proof of income tended to receive lower APR percentage as well. Because such statuses reflect the borrower's personality to be more trustworthy.


## Key Insights for Presentation

First, histogram plot were created to visualize the distribution on borrower based on various factor(such as: proof of income, previous loan records etc). And histogram plots of borrower's APR percentage are made for each Prosper Score level(1-11). ProsperScore has the strongest relationship with Borrower's APR (negatively correlated). Point plot were also created to find out the relationship between BorrowerAPR and various factors(loan records, proof of real estate and income). Finally, The third heatmap(Occupation vs Listing Category) was made So that the creditor(Prosper) could decide optimum APR for each potential borrower in the future.
