# Exploring Prosper loan Dataset
## by Ediong Alexander


## Dataset
The dataset contains information on 113937 loans listings collected from a loan company, Prosper from 2005-11-09 - 2014-03-10. The dataset contains information such as the listing keys, date loan was listed, loan status, etc. The dataset was provided by Udacity and can be found [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv). Information on the columns can also be found [here](https://docs.google.com/document/d/e/2PACX-1vQmkX4iOT6Rcrin42vslquX2_wQCjIa_hbwD0xmxrERPSOJYDtpNc_3wwK_p9_KpOsfA6QVyEHdxxq7/pub)


## Summary of Findings
Carrying out the explorations I was able to find that employment status does have an effect on the loan status. It didn't seem so at first but after graping the percentage of of different employment status, I was able to find out that about 40% of listings were employment status was unavailable defaulted on their loans, followed by retired then unemployed persons. Listings where employment status was 'employed' had the least percentage of defaulters. I also found that defaulted and past due loans tend to have high APR, on further investigation I found that APR is higher for high risk loans i.e loans with high estimated average annualized loss rate. So this transcends into the defaulted loans. 
<br>
In addition, I found that APR has a negative relationship with Income, which means the higher the income the lesser the APR. 

## Key Insights for Presentation

For the presentation, I will be focusing on the following insights
1. Defaulted loans are associated with high APR. This was further investigated to find that the higher the Estimated Avg. Annual Loss Rate which is represented by Prosper ratings, the higher the APR. So loans with high APR are high risk loans.
2. Individuals with higher and stable income received lower APR on their loans.
3. Most employed individuals do not default on their loans.
