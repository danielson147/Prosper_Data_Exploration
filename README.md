# (Dataset Exploration Title)
## by (your name here)


## Dataset

> There are 113937 customers in the dataset with 81 features. 
We are focusing our exploration on about 10-15 features in the dataset. 
Most variables are numeric in nature, but the variable ProsperRating(Alpha)
 is an ordered factor variable with the corresponding numeric values captured in ProsperRating(Numeric). 
They have the following levels. (worst) ----> (best) 
ProsperRating(Alpha): HR, E, D, C, B, A, AA ProsperRating(Numeric): 1, 2, 3, 4, 5, 6, 7
Prosper as a company, considering the currency of this dataset (which was 2017), 
as 56,576 current loans that are running. About 38,074 ones have been completed, 5,018 defaulters while only 5 are cancelled.  

## Summary of Findings are:
1. The company need to be more specific about their Know Your Customer(KYCs) detials. They have about 25,000 customers that has occupation 
categorize as 'Other' and 'Professional'  
2. There are 83% customers that are gainfully employed. This is the total for 'Employed' and 'Full-time' 
3. 7% of the customer base has source of income that cannot be verified. 
This will lead to customers dissatisfaction as this number will have their loan request denied.
4. There is a strong positive correlation between BorrowerAPR, LenderYield and EstimatedReturns. 
High BorowerAPR is expected to lead high LenderYield and high EstimatedReturn.
5. As expected, customers with that are employed and also with full-time employ have more verifiable income than others.  

> Summarize all of your findings from your exploration here, whether you plan on bringing them into your explanatory presentation or not.
The 'BorrowerAPR' has a positive correlation with 'EstimatedReturn'. Rather than being discouraged, lenders should be encouraged to invest more. 
Prosper as a company should more developing products for customers that are in full time employment, since they generate about 83% revenue for the company. 

## Key Insights for Presentation

> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.
1. Distribution of 'LoanStatus' in the dataset(17)
2. Distribution of 'LenderYield' in the dataset. (19)
3. Heatmap showing the correlation between the numeric variable of considerations.(35)
4. BorrowerAPR vs LenderYield(39)
5. 'EmploymentStatus', 'BorrowerAPR' and 'LoanStatus' for selected 'LenderYield'. (76) 