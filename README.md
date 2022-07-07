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

ANALYSING STATE COLUMN

![image](https://user-images.githubusercontent.com/100566501/177732838-a3cc8fd9-de24-4242-acdd-50da8b65e70b.png)
![image](https://user-images.githubusercontent.com/100566501/177732863-45ef4875-ade4-48ca-a032-ba554d73cc45.png)
![image](https://user-images.githubusercontent.com/100566501/177732880-29c72650-2915-486e-b971-c872d0bf377c.png)

There is 51 unique state present who have different churn rate.

From the above analysis CA, NJ, TX, MD, SC, MI are the ones who have a higher churn rate of more than 21.

The reason for this churn rate from a particular state may be due to the low coverage of the cellular network.

ANALYSING "INTERNATIONAL PLAN" COLUMN

![image](https://user-images.githubusercontent.com/100566501/177732997-de4efa77-b0ba-4484-a31d-dbaf2f6b1263.png)
![image](https://user-images.githubusercontent.com/100566501/177733045-51bfc3aa-78e6-4a08-b884-a906eba1ec59.png)
From the above data we get
There are 3010 customers who don't have a international plan.
There are 323 customers who have a international plan.
Among those who have a international plan 42.4 % people churn.
Whereas among those who don't have a international plan only 11.4 % people churn.
So basically the people who bought International plans are churning in big numbers.
Probably because of connectivity issues or high call charge.

ANALYSING "CUSTOMER SERVICE CALLS" COLUMN

![image](https://user-images.githubusercontent.com/100566501/177733445-677ef2c8-b635-4564-8934-84c2ba32e913.png)
It is observed from the above analysis that, mostly because of bad customer service, people tend to leave the operator.
The above data indicating that those customers who called the service centre 5 times or above those customer churn percentage is higher than 60%,
And customers who have called once also have a high churn rate indicating their issue was not solved in the first attempt.
So operator should work to improve the service call.

ANALYSING ALL CALLS, ALL CALLS CHARGE TOGETHER

As these data sets are numerical data type, so for analysing with the 'churn' which is a categorical data set, We are using mean, median, and box plots.
![image](https://user-images.githubusercontent.com/100566501/177733639-0a820d3f-c141-487f-9e21-71be06fc3199.png)
![image](https://user-images.githubusercontent.com/100566501/177733680-c5bb0178-09ca-4ce7-b977-8290bd3da558.png)
![image](https://user-images.githubusercontent.com/100566501/177733706-75c40ce3-9ec4-441a-9852-57199a33abca.png)
![image](https://user-images.githubusercontent.com/100566501/177733728-a54547ed-e8ba-44ae-a6dc-e6a3c933a688.png)
![image](https://user-images.githubusercontent.com/100566501/177733842-bfab1ae7-8443-4376-b3cb-5f563e232f3d.png)
![image](https://user-images.githubusercontent.com/100566501/177733879-0e810eed-dd0d-4bef-96b0-be82ae5d0e12.png)
![image](https://user-images.githubusercontent.com/100566501/177733902-0517548a-f3ac-4845-b255-e4fe0adcbbe2.png)
![image](https://user-images.githubusercontent.com/100566501/177733932-3d4e3d54-7100-419d-b62d-682c18bed94f.png)
![image](https://user-images.githubusercontent.com/100566501/177734019-6d8e5f89-70e2-41b7-8d71-875b4e857b61.png)
After analysing the above dataset we have noticed that total day/night/eve call/charges are not put any kind of cause for churn rate. 
But international call charges are high as compare to others it's an obvious thing but that may be a cause for international plan customers to churn out.

GRAPHICAL ANALYSIS

UNIVARIATE ANALYSIS

In Univariate Analysis we analyse data over a single column from the numerical dataset, for this we use 3 types of plot which are box plot, strip plot, dis plot.

![image](https://user-images.githubusercontent.com/100566501/177734440-eb3851ad-a1c2-4598-b1ff-4b2afd2e1cfc.png)
![image](https://user-images.githubusercontent.com/100566501/177734472-8e403033-24dc-4b8b-a199-3e8d0d35bf81.png)
![image](https://user-images.githubusercontent.com/100566501/177734541-c9992583-7c93-4290-97a3-cae87ec70491.png)
![image](https://user-images.githubusercontent.com/100566501/177734560-f05f693c-3174-481e-8d6e-9d80ccb2373e.png)
![image](https://user-images.githubusercontent.com/100566501/177734592-ce7c7a12-66dc-4b87-a0b8-c6d8ba6005aa.png)
![image](https://user-images.githubusercontent.com/100566501/177734684-59355cba-5d38-40b5-b9dd-31053add81d7.png)
![image](https://user-images.githubusercontent.com/100566501/177734718-289fe60d-aba4-40cb-aa59-5d4626d91aba.png)
![image](https://user-images.githubusercontent.com/100566501/177734743-e1eb7c09-c420-48d7-b5a6-192069c0904c.png)
![image](https://user-images.githubusercontent.com/100566501/177734762-c260d994-327b-42d3-ba38-0e5d4365f6c6.png)
![image](https://user-images.githubusercontent.com/100566501/177734785-72c60031-32c9-4c93-b580-f103eed7c24f.png)
![image](https://user-images.githubusercontent.com/100566501/177734803-105d7529-eeac-41a2-a9a3-36497397ed3d.png)
![image](https://user-images.githubusercontent.com/100566501/177734831-2def002c-995c-4c1f-bd12-f20a8a4efd91.png)


![image](https://user-images.githubusercontent.com/100566501/177734927-4a8128e3-3409-47d4-a944-c1944f4b080b.png)
![image](https://user-images.githubusercontent.com/100566501/177735026-5760ef2b-c2bf-48a8-ae96-6df1cd1d9463.png)
![image](https://user-images.githubusercontent.com/100566501/177735066-72d42dee-17b5-46ea-9a9a-33760b18fe61.png)
![image](https://user-images.githubusercontent.com/100566501/177735113-308df198-7102-466d-8f29-691755bfcf02.png)
![image](https://user-images.githubusercontent.com/100566501/177735173-9550b53f-aaf7-4273-b680-9867cd25e3d3.png)
![image](https://user-images.githubusercontent.com/100566501/177735250-c048f05e-e0d2-4674-b26e-ad006b3ee196.png)
![image](https://user-images.githubusercontent.com/100566501/177735269-1bd9be5d-8316-4e1a-9482-f8b8a64acceb.png)
![image](https://user-images.githubusercontent.com/100566501/177735298-841f0814-d3aa-46f9-a95e-55d27faf806c.png)
![image](https://user-images.githubusercontent.com/100566501/177735311-3fe6741e-9d54-4313-8a72-a0a204e2bb20.png)
![image](https://user-images.githubusercontent.com/100566501/177735349-89dd5189-9433-4121-9c85-4392e32de01b.png)
![image](https://user-images.githubusercontent.com/100566501/177735381-298e6e43-1f8b-4cdd-8b06-3331fe7a3b67.png)
![image](https://user-images.githubusercontent.com/100566501/177735412-dc2797bd-0696-43b6-8971-1466395f6dc4.png)

![image](https://user-images.githubusercontent.com/100566501/177735641-124298cb-7fae-4b29-bac1-bb28f5c7da5e.png)
![image](https://user-images.githubusercontent.com/100566501/177735674-d2d9d556-bb13-43f0-9047-fc93fd1c4e26.png)
![image](https://user-images.githubusercontent.com/100566501/177735722-683b2e75-a219-4b84-af68-31590418291d.png)
![image](https://user-images.githubusercontent.com/100566501/177735724-8be403c7-e873-4d2e-b134-ce21af218966.png)
![image](https://user-images.githubusercontent.com/100566501/177735772-ee381a6f-3d87-4293-82ce-1aa5d6755edb.png)
![image](https://user-images.githubusercontent.com/100566501/177735800-8ec15f84-408f-4bbd-b4f4-54e08417eeb4.png)


BIVARIATE ANALYSIS

In Bivariate Analysis we analyse data by taking two columns into consideration from a dataset, here we only take numerical data type column, for this visualization we use Box plot, scatter plot

![image](https://user-images.githubusercontent.com/100566501/177736388-ebacb2c8-d2ee-4d3e-ab3a-7ef04cb03a77.png)
![image](https://user-images.githubusercontent.com/100566501/177736424-51a6bfff-a68c-415f-8d21-1c879a96c6e7.png)
![image](https://user-images.githubusercontent.com/100566501/177736446-c96fe2ff-cab9-423b-92a6-2aa9b4171b67.png)
![image](https://user-images.githubusercontent.com/100566501/177736475-39b357da-a400-4ad2-a171-9cc639beb2dc.png)


