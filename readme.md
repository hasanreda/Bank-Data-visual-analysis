# (Dataset Exploration Title)
## by (your name here)


## Dataset

There are 9228897 cells in the dataset with 113937 rows and 81 columns, most columns contain numeric variables.

## Summary of Findings

For loan amounts, the distribution was symmetrical univariate and has many spikes with multiples of 5k usd, this is interesting as it might mean different interest rates or features for loans with amounts that are multiples of 5k usd than other loan amounts.

For Stated monthly income the distribution was nonuniform with many frequency spikes.

Most borrowers under about 8.2 k usd monthly income don't make loans over 25k usd and from the scatter plot it seems that they tend to take lower loans the lower their salaries are but still the frequency spikes exist at multiples of 5k usd, borrowers with more than about 8.2k usd monthly income tend to take 35k usd loans more than other loans that are in the range of 26:35 k usd.

Student loans combined compose the biggest sole borrower type. Most Occupations have average loans that are less than 5k and close in value while some occupations such as 'judge' had an average over 10k usd.

There is a surprising variety in income between each occupation and another is opposite to the commonality between loan amounts between each occupation, this interacts with the conclusions that stated the correlation between monthly income and loan amounts under 8.2k, where even though some occupations have a big difference in monthly income but their loan amounts are mostly common (under 8.2k) and only a small portion of occupations increase the Original loan amounts average.

Most borrowers who work in sales get chargedoff but their majority don't get defaulted.

Although the number of borrowers who get defaulted are less than ones who are chargedoff but they are both correlated in the same occupation.

Some occupations such as "Dentist" and "Construction"  didn't get chargedoff while other occupations as "Attorney" and "biologist" didn't get defaulted, Judge had nan values for both statuses and didn't get displayed.

Most occupations that get defaulted and charged off are of an unstable nature and would likely be jobs that depends on gigs or short contracts.

36 months term loans are expected to be defaulted or chargedoff more than three times as much as 12 and 60 months term loans each.

Borrowers with employment statuses as "full-time" make the biggest portion of defaulted and chargedoff loan statuses. employment statuses as "nan" and "not available" are the only statuses that has a bigger defaulted loans than chargedoff loans.

People with "not available" employment statuses have the highest expectations not to deliver their loans.

Although "employed" and "full-time" employment statuses made most of the defaulted and charged off loans, but their expectations to not deliver loans are (6 , 28) % which is close to other employment statuses.

"Retired" made the most percentage of loans that weren't delivered.

Borrowers not owning a home have 23% more chance not to be able to deliver their loans.
## Key Insights for Presentation

I aimed on putting focus on the main incomplete and noncurrentloan statuses due to the difference between different occupations in counts, this relationship will be between the ratio of (defaulted/charged off) occupations to the total no of borrowers with that occupation individually in a collective comparison, and see their correlations with occupation ,loan amounts, income and dept to income ratio.