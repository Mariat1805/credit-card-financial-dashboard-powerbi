# Dataset Information

This project uses two datasets:

## customer.csv

Contains customer demographic and profile information:

- Client_Num
- Customer_Age
- Gender
- Education_Level
- Marital_Status
- Income
- Customer_Job
- State
- Cust_Satisfaction_Score

## credit_card.csv

Contains transaction and credit card activity information:

- Card_Category
- Credit_Limit
- Total_Trans_Amt
- Total_Trans_Vol
- Avg_Utilization_Ratio
- Interest_Earned
- Delinquent_Acc
- Exp Type
- Use Chip

## Data Model

Relationships:

customer[Client_Num] → credit_card[Client_Num]

DateTable[Date] → credit_card[Week_Start_Date]
