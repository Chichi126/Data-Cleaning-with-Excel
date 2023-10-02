# Data-Cleaning-with-Excel

1. **Id:** A unique identifier for each customer support interaction.

2. **Customer_Name:** The name of the customer who initiated the support interaction

3. **Sentiment:** The sentiment or emotional tone expressed during the interaction, categorized as "Very Positive," "Positive," "Neutral," "Negative," or "Very Negative."       This column indicates the customer's emotional response.


4. **Call_Timestamp:** The timestamp or date when the customer made the support call or initiated the interaction.

6. **Reason:** The reason or purpose for the support interaction, such as "Billing Question," "Service Outage," or "Payments." This column provides insight into the nature     of the customer's inquiry or issue.

7. **City:** The city where the customer is located.

8. **state:** The state where the customer is located.

9. **Channel:** The communication channel used for the support interaction, such as "Call-Center" or "Chatbot." This column indicates how the customer reached out for          support.

10. **Response_Time:** The response time, categorized as "Within SLA" (Service Level Agreement) or "Above SLA." It indicates whether the support response time met the           agreed-upon service level.

11. **Call Duration In Minutes:** The duration of the support call in minutes, which measures the length of the customer's interaction with the support team.

12. **Call_Center:** The call center or support center associated with handling the customer's inquiry or issue.


To check out for duplicate values
![image](https://github.com/Chichi126/Data-Cleaning-with-Excel/assets/140970592/8c55045a-31f1-4d4e-968a-4e9095f6223d)

![image](https://github.com/Chichi126/Data-Cleaning-with-Excel/assets/140970592/806d519b-1842-43e4-a7f0-fb0361f79dae)



To format the time column
I first highlighted the time column and navigated to Data, then Text- to-column and left the delimiter unchanged, clicked on Date and changed the date format to MDY and clicked on finish

![image](https://github.com/Chichi126/Data-Cleaning-with-Excel/assets/140970592/be8cb3f7-7683-4d76-8294-9d90c11075bd)

To capitalize the first letters of the column, I started by inserting a new row A2, and then entered the Formula below

![image](https://github.com/Chichi126/Data-Cleaning-with-Excel/assets/140970592/c1b02ea4-1906-4e69-875e-beb814c02da5)

 
So as to retain the result from the formula, I copied my result, then clicked on A2 again  but navigated to the Home tab and Paste then clicked on values to paste it back, then went ahead to delete the rows containing the unedited column title

![image](https://github.com/Chichi126/Data-Cleaning-with-Excel/assets/140970592/fb69cd96-f555-44a3-bd9f-94d1d9804807)


![image](https://github.com/Chichi126/Data-Cleaning-with-Excel/assets/140970592/e0855673-505b-4880-916f-33b1aaf06212)


To create a new column named Day, I first inserted a new column and typed in the formula

![image](https://github.com/Chichi126/Data-Cleaning-with-Excel/assets/140970592/06366b86-18f2-4ac1-bef8-2222664eb390)

Next was to remove the C_SAt column cause I will not be using it in my analysis

![image](https://github.com/Chichi126/Data-Cleaning-with-Excel/assets/140970592/c3271a7c-6930-4726-8bb7-7ea609d45c0d)


After ensuring that my dataset was clean and ready to work with, I moved on to start analyzing with pivot table

**Pivot Table** 

I started by clicking on one of the cells inside the table, navigated to the Insert tab then clicked on Pivot Table

![image](https://github.com/Chichi126/Data-Cleaning-with-Excel/assets/140970592/5121a16b-b479-4079-8d12-5baf9757633b)

![image](https://github.com/Chichi126/Data-Cleaning-with-Excel/assets/140970592/621aded3-4f18-4af7-88d4-f322e84583e0)


To select the columns I will be analyzing 

![image](https://github.com/Chichi126/Data-Cleaning-with-Excel/assets/140970592/b1fed7db-7836-4b2b-a57b-c41da06dc52a)


To change the channel Pivot table to a Percentage

I started with coping the Channel 

![image](https://github.com/Chichi126/Data-Cleaning-with-Excel/assets/140970592/04d38b32-aa87-4183-9b4c-0f4f597fd194)


![image](https://github.com/Chichi126/Data-Cleaning-with-Excel/assets/140970592/c04ac9ec-43e9-4c35-80e4-069b4c4b5b1a)


![image](https://github.com/Chichi126/Data-Cleaning-with-Excel/assets/140970592/775b8825-6810-4e45-9ed0-eb5af8026909)


![image](https://github.com/Chichi126/Data-Cleaning-with-Excel/assets/140970592/a124cda7-1e5a-466e-b920-6c703da1ab47)


![image](https://github.com/Chichi126/Data-Cleaning-with-Excel/assets/140970592/4096199f-98eb-4785-8a4f-3275dd01eb7e)


![image](https://github.com/Chichi126/Data-Cleaning-with-Excel/assets/140970592/550cbae2-8110-4b03-beab-8ec41b4df427)


![image](https://github.com/Chichi126/Data-Cleaning-with-Excel/assets/140970592/52de3643-b03f-4b6f-918a-2526dce8c68a)


















 



 


Next was to 
To change the channel Pivot table to a get percentage I changed 

 
The pics of the transpose 
  
 
My Pivot Table
 













 
