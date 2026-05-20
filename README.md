# Loan-Risk-Customer-Default-Analysis-For-CrediTrust

## INTRODUCTION
This project analyzes customer loan risk data to identify factors associated with loan default. The analysis aims to help  CrediTrust improve loan approval decisions, reduce financial risk, and develop better lending strategies.

 
## OBJECTIVES
The objectives of this analysis are:
* To identify risky customer profiles 
* To evaluate factors influencing loan default 
* To determine whether loan conditions should be stricter 
* To assess if loan amounts should be reduced for certain customers 
* To build a simple predictive model for default risk


## DATA CLEANING AND PREPARATION
The dataset was cleaned and prepared before analysis. Initial exploration was performed using functions such as head(), info(), and shape() to understand the dataset structure. Missing values were identified and handled appropriately to improve data quality. Customer risk categories were created based on credit score and previous default history. Credit scores were also grouped into categories to simplify analysis. Finally, grouped summaries and aggregations were prepared to support visualization and default risk analysis.

## Distribution of Credit Scores
<img width="533" height="298" alt="Loan 0 9" src="https://github.com/user-attachments/assets/e1f71c0f-5466-48e1-bd02-31cb87a0c4ea" />

## Loan Purposes
<img width="842" height="249" alt="Loan 1 1" src="https://github.com/user-attachments/assets/aadd5253-774a-4e69-8470-2e765b12d465" />

## Default Rate by Credit Score Group
<img width="856" height="247" alt="Loan 1" src="https://github.com/user-attachments/assets/911dbcc2-d211-476d-88b7-dee58b8694f9" />

## Default Rate by Previous Default History
<img width="864" height="337" alt="Loan 2" src="https://github.com/user-attachments/assets/6e561be0-6cf3-4e5b-8ad1-84759c6f54ea" />

## Distribution of Customer Risk Categories
<img width="601" height="425" alt="Loan 3" src="https://github.com/user-attachments/assets/fc9ffefc-8160-4de3-86ce-5d18bdb45355" />

## Loan risk and Default Analysis
<img width="602" height="425" alt="loan 4" src="https://github.com/user-attachments/assets/416594ea-588b-4251-a571-65d5d2d35160" />

## Insight

1. What type of customers should the company avoid?

The company should avoid or carefully review customers with:
* Previous default history 
*	Low credit scores 
*	Unstable employment status 
*	High-risk classifications
  
These customers demonstrated significantly higher default rates and therefore pose greater financial risk to the company.
 
2. What loan conditions should be stricter?
   
Loan conditions should be stricter for customers identified as high risk. The company should:
* Require higher credit score thresholds
* Conduct stricter background checks
* * Request additional financial documentation 
*	Apply shorter repayment periods 
*	Increase monitoring for customers with previous defaults
  
These measures can help reduce the probability of loan default.

3. Should the company reduce loan amounts for certain customers?
 
Yes. Loan amounts should be reduced for customers with:
*	Poor credit scores 
*	Previous default records 
*	High debt risk indicators 
*	Unstable employment status
*	Reducing loan exposure for high-risk customers can minimize potential financial losses while still allowing controlled access to credit.


## Conclusion

The analysis revealed that previous default history, low credit scores, and unstable employment are strong indicators of loan default risk. The company should strengthen approval policies and reduce exposure to high-risk customers.
