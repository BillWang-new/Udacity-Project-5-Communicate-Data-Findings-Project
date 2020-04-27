# Loan Data Exploration
## by Xiangbo Wang


## Dataset

The dataset consisted of borrower APRs and attributes of 113,937 loans. There are totally 81 attributes included in the original data set. The main focus on this project is to find out the some of the interested attributes that could potentially affect borrower's APR. This include original loan amount, borrower's Prosper rating, loan term, borrower's stated monthly income, as well as borrower's employment status. Since some of the attributes only avaliable afer July 2009, some old loans are removed from original data set. This gives us totally 84,853 loans that relevant to this project. The dataset can be found [here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1554486256021000) with Prosper Data Dictionary to Explain Dataset's Variables [here](https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1554486256024000)


## Summary of Findings

In the exploration, I found that there is a weak negative correlation of -0.426 between borrower APR with Loan Original Amount. This means when Loan Original Amount increases, the boirrower APR decrease. However, since it is a weak negative correlation, the changes is not very significant. Borrower APR can also be affected by other categorical variables in different levels such as loan term, employment status and Prosper ratings. In general, loan term can hardly affect Borrower APR, then people with more secured jobs tend to have lower APR and Prosper ratings is the most feature that affect borrower APR among all three. The better prosper rating a borrower have, the lower APR this borrowe will get.

Outside of the main variable of intere, I found that comparing with employment status and terms, there is a positive relationship between terms and Loan Original Amount. The longer a loan term is, the larger amount a borrower wish to get.

## Key Insights for Presentation

For the presentation, I will focus on explaining features that could relatively affect the borrower APR, which are original loan amount, Prosper rating. I started by showing the distribution of borrower APR and other categoriy variables. Then, I will show the relationship between APR vs. loan amount. After that I will show the relationship from Borrower APR across Rating and Status. Finally, I will show the relationship from Loan Original Amount across Status and Term as an extra outside of key insterest of the presentation.