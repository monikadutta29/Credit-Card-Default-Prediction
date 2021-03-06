# Credit-Card-Default-Prediction
__Objective__ – Predict the probability of a customer defaulting payment for the credit card the subsequent month, based on past information. The past information is provided in the dataset. This probability will help the collections team to prioritise follow up with customers who have a high propensity of defaulting.

## About the dataset
This dataset contains information on default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005.

1.	__DEFAULT__ - Default payment next month (Yes=1, No=0)
2.	__LIMIT_BAL__ - Amount of the given credit (NT Dollar)  
3.	__SEX__ - Gender (1 = male; 2 = female)
4.	__EDUCATION__ - Education (1 = graduate school; 2 = university; 3 = high school; 4 = others)
5.	__MARRIAGE__ - Marital Status (1 = married; 2 = single; 3 = others)
6.	__AGE__ - (in years)
7.	__PAST_PAY__ - History of repayment status
    <br> -  PAY_1 = the repayment status in September 2005
    <br> -  PAY_2 = the repayment status in August 2005
    <br> -  PAY_6 = the repayment status in April 2005
    
    <br> -  The measurement scale for the repayment status is
    
    i. -2 = no consumption <br>
    ii. -1 = pay duly <br>
    iii. 1 = payment delay for one month <br>
    iv. 2 = payment delay for two months <br>
    v. 8 = payment delay for eight months <br>
    v. 9 = payment delay for nine months and above <br>
        
8.	__BILL_AMT__- Amount of bill statement (NT Dollar)
    <br> -  BILL_AMT1 = amount of bill statement in September 2005
    <br> -  BILL_AMT2 = amount of bill statement in August 2005
    <br> -  BILL_AMT6 = amount of bill statement in April 2005
    
9.	__PAY_AMT__ - Amount of previous payment (NT Dollar)
    <br> -  PAY_AMT1 = amount paid in September 2005
    <br> -  PAY_AMT2 = amount paid in August 2005
    <br> -  PAY_AMT6 = amount paid in April 2005
