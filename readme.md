#  Prosper Loan Data
## by Abanoub Aziz
***


## Dataset
***


This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others supplied by a credit company called Propser. Prosper or Prosper Marketplace Inc. is a San Francisco, California based company specializing in loans at low interest rates to the borrowers.

For the purporse of this investigation I will be considering the following variables:
>Term, LoanStatus, BorrowerRate, ProsperRating (Alpha), ProsperScore, ListingCategory (numeric), BorrowerState, EmploymentStatus, DelinquenciesLast7Years, StatedMonthlyIncome, LoanOriginalAmount, LoanOriginationDate.


## Summary of Findings
***

>* It seems that Defaulted and Chargedoff loans tend to have a higher BorrowerRate than Completed loans, this is likely due to the fact that high risk loans have a higher rate than low risk loans.
>* 36 months payment plan tend to be the loan most likely to Default/Chargeoff with the 12 months plan being the least likley.
>* It seems that Defaulted and Chargedoff loans tend to have a slightly lower LoanOriginalAmount than Completed loans, this is likely comes from the fact that lenders tend to provide a lower loan amount to higher risk lenders since they are more likely to default on loans
>* The proprtion for defaulting increases for Business loans (9.7% to 12.1%) and decreases for Home Improvement loans (11.7% to 9.8%) and for a similar result also occurs for the ChargedOff loans in which the proportaions increases for Business loans (9.7% to 13.1%) and decreases slightly for Home Improvement loans (11.7% to 11.5%)
>* It seems that the D Prosperrating is the most likley rating to default/Chargeoff on loan payments, while the ProsperScore shows that a borrower with a score of 6 is the most likeley to default/Chargedoff on loans. Intrestingly HR and 1 seems to not have the same likelyhood to default as mid range borrowers, this is likeley due to the number of loans given out to high risk borrowers being lower, and that borrowers defaulting on payment get moved down to a lower rating when trying to take another loan and will be more likeley to pay off the loan to not incur further debt
>* Borrower from California are most likley to default on loan payments, followed by Florida and New York while borrowers from Kansas are most likely to complete their loan payments
>* The proportions for borrowers defaulting/chargeoff on loans are very similar to borrowers who complete the payment for their loans, with only the "other" employment category increase the rate by almost double from 2.3% to 5.4% and 5.5%, for ChargedOff and Defaulted payments respectively, overall the effect here seems to be negligible
>* Borrowers with completed loans tend to have a higher income on average than borrowers who default/Chargeoff on loans
>* Regarding the PropserRating variabe, the worse the ProsperRating, the longer the term of the loan is, the higher the BorrowerRate, the higher the number Delinquencies in the Last 7 Years, however the stated monthly income is quite similar across all prosperRating with a small decrease the worse the rating is and the Loan original amount it seems that lenders tend to provide a lower loan amount for higher risk borrowers


## Key Insights for Presentation
***

>*The most intresting relationship is the least expected one where D ProsperRating/ProsperScore of 6 is the most likley to default/chargeoff on loan payments, at first this seems illogical but upon futher thought this most likley came from the fact that lenders would avoid higher risk borrowers in favor of slightly lower risk ones.
>*The fact that High Risk borrowers were only given 36 month loan with no 12 or 60 months terms.
>*The fact that borrowers from California, the 2nd most costly state in terms of living expenses had the most likely change of defaulting on loans, while borrowers from Kansas were the least likely