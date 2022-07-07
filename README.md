# Telecommunication-visualisation
INTRODUCTION:
Customer churn means shifting from one service provider to its competitor in the market. ... The telecom service providers strive very hard to sustain in this competition. So to sustain this competition they often try to retain their customers than acquiring new ones as it proved to be much costlier.

UNDERSTAND MORE ABOUT THE DATA:
Breakdown of Our Features:
State: 51 Unique States name.
Account Length: Length of The Account.
Area Code: Code Number of Area having some States.
International Plan: Yes Indicate International Plan is Present and No Indicates no subscription for International Plan.
Voice Mail Plan: Yes Indicates Voice Mail Plan is Present and No Indicates no subscription for Voice Mail Plan.
Number vmail messages: Number of Voice Mail Messages ranging from 0 to 50.
Total day calls: Total Number of Calls made in Morning.
Total day charge: Total Charge to the Customers in Morning.
Total eve calls: Total Number of Calls made r in Evening.
Total eve charge: Total Charge to the Customers in Morning.
Total night calls: Total Number of Calls made in Night.
Total night charge: Total Charge to the Customers in Night.
Customer service calls: Number of customer service calls made by customer.
Churn: Customer Churn, True means churned customer, False means retained customer.

CHECKING FOR MISSING AND DUPLICATE VALUES
![image](https://user-images.githubusercontent.com/100566501/177731662-c3b99677-2c5d-4491-b048-64da216d1660.png)
• As of now There are 3333 rows and 17 columns in above dataset.
• out of which there are 1 Boolean data type i.e. churn
• 8 float data type,
• 8 integer data type,
• 3 object data type i.e. categorical value are there.
• There are some missing value present,
• And there are no duplicate value present.

EXPLORATORY DATA ANALYSIS OF THE DATA SET
ANALYZING WHAT THE DEPENDENT VARIABLE SAID TO US I.E 'CHURN'.
![image](https://user-images.githubusercontent.com/100566501/177732184-c3b04997-8893-4163-a2cb-0a4ea50184ee.png)
![image](https://user-images.githubusercontent.com/100566501/177732199-edd16f4b-0add-4c13-b881-d7761f824e39.png)
![image](https://user-images.githubusercontent.com/100566501/177732220-421b9e42-9be8-444d-b37c-2d065a9f2ec3.png)
After analysing the churn column, we had little to say like almost 15% of customers have churned. let's see what other features say to us and what relation we get after correlated with churn.
![image](https://user-images.githubusercontent.com/100566501/177732320-5ec13bff-6145-4d47-9f89-b628844749ac.png)

ANALYSING STATE COLUMN
There is 51 unique state present who have different churn rate.

From the above analysis CA, NJ, TX, MD, SC, MI are the ones who have a higher churn rate of more than 21.

The reason for this churn rate from a particular state may be due to the low coverage of the cellular network.
