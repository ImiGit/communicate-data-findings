# Prosper Loan Data Exploration
## by Iman Babaei


## Dataset

> The data consists of information for 113,937 loans with 81 variables for each
loan from 2005 to 2014. To investigate the aspects affecting the annual 
percentage rate, I chose 17 numerical and categorical variables like loan amount,
borrower rate, current loan status, borrower income range, and etc. The original
dataset can be found [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1554486256021000).


## Summary of the Findings

In the exploration, the strongest relationship I found was between credit 
score range and Prosper rating category. The main reason might be that in 
Prosper rating system credit score plays the most important role. I saw that 
through years the interest rate has increased with a maximum at 2011 and then
decreased. Cosmetic procedures and household expenses have the highest interest
rate while personal expenses and boat have the lowest. I found that the average 
interest rate for the best Prosper rating category is less than third compared
with the worst rating category. Looking at credit score upper ranges also showed
the same trend, the higher the credit score, the lower the interest rate. 
Interest rate for different loan terms was different but since the sizes of each
term was significantly different looking at it was kind of a dead-end.

Another finding was that people with higher income ranges were paying lower 
interest rates. Further investigation of credit scores for different income range
groups showed that the distribution in each category is vast and while the income
range group increases, the median credit score does not necessarily increase. 
Again proving that credit score is important in determining the interest rate.

Looking at the loan status for different income ranges illustrated that the
percentage of the charged off loans decreases with increase in the income range.
The past due percentage remains more or less the same among groups. Also, I saw
that by increasing the income range the percentage of a longer term loan (60 months)
increases and 36 month term loan decreases.


## Key Insights for Presentation

For the presentation part, I decided to focus on the interest rate variance in
different income range groups.

First, I looked at the interest rate changes through years for different income
ranges. Interest rates change through years for all of the income range groups. 
But, for the higher income ranges the interest rates are lower always and the 
ironically the gap between the interest rates for different groups has increased
in the past years! For further understanding of the Income Range effect, the 
number of loans for each Income Range during past years was plotted as well.

Then I looked at interest rate for different Prosper ratings categories. The 
better the prosper rating, the lower the interest rate they pay. The violin 
plot proved it that the better rated categories pay up to one third lower rates.

Finally, to dig dipper, I showed the change of interest rate vs Prosper ratings
and with regard to the credit score. It was shown that the better rated borrowers
have higher credit scores and pay lower rates.