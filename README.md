# Mortgage Prediction using RAPIDS

<center>
  
![](https://wp-krypton.s3.amazonaws.com/wp-content/uploads/sites/3/2019/01/loan-to-value-620x330.jpg)

</center>


## Why predict Loan Amount? 

Customers have to always face the problem of having to go through all procedure of loan issue to get to know an estimate of the loan amount and sometimes the amount change when issued.

By automating the loan amount to the customers. They can have a faster estimate which will lead them to make a faster decision on taking a mortgage from Bank or Finance Company.

Also, predict Loan Amount can help Bank or Finance Company with their marketing campaigns. By predicting Loan Amounts they can enhance the marketing campaigns and use the prediction in their website or app to attract more people to use their Finance Servises.


## Data 

Dataset is derived from [Fannie Mae’s Single-Family Loan Performance Data](https://capitalmarkets.fanniemae.com/credit-risk-transfer/single-family-credit-risk-transfer/fannie-mae-single-family-loan-performance-data) with all rights reserved by Fannie Mae.

The sample data used in this project is **2020 3rd Quarter** with dimension 2,771,993 rows and 108 columns. The same data used in this project is provided in this repo data folder.

The target is **Original UPB** The dollar amount of the loan as stated on the note at the time the loan was originated.

Here you can find the [columns description](https://loanperformancedata.fanniemae.com/lppub-docs/FNMA_SF_Loan_Performance_Glossary.pdf) for the data.

## Results and Findings

### Findings

Through exploring this data I found the following insights: 

- Retail origination channel is of utmost use by the party that delivered the loan to the issuer. 

- The numbers of customers joining Homeready Program in the 3rd Quartier is very low in comparison with customers issuing mortgage but not in Homeready Program.

- Majority of customers choose to not have Mortgage Insurance.

- Loan Purpose for the newest loans is either a refinance mortgage or a purchase money mortgage.

- Most of the customers[borrower or co-borrower] issuing a mortgage are not qualifies as a first-time homebuyer.

### Model Results

The model I created was to predict the Loan amount and here you can see the model performance. Where the MSE was **VALUE** So the prediction is off only by **VALUE**.
So now the customer can has a prediction for loan amount with considering **VALUE** range of mistake.

