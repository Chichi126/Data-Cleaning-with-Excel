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


**The Pivot Table**


![image](https://github.com/Chichi126/Data-Cleaning-with-Excel/assets/140970592/550cbae2-8110-4b03-beab-8ec41b4df427)



**My Dashboard**

I created a chat first for each pivot table

![image](https://github.com/Chichi126/Data-Cleaning-with-Excel/assets/140970592/25eed6ad-c52c-424e-9231-e2d4ba8625d1)

Next was to create a slicer and connect all my charts for easy interaction, clicked on any of the slicers, went to the Slicer tab, and then  navigated to report connection and check on the pivot table's name

![image](https://github.com/Chichi126/Data-Cleaning-with-Excel/assets/140970592/8f3e0d1d-a629-426a-b4d6-5891a4efbbca)

![image](https://github.com/Chichi126/Data-Cleaning-with-Excel/assets/140970592/8753d7e9-fc44-4bac-9595-5fb74bafc6e4)


# Call_Center Dashboard

![image](https://github.com/Chichi126/Data-Cleaning-with-Excel/assets/140970592/4b8a4e30-294c-49b3-8057-137bffde0060)



# Observation 


1. **Call Volume:** The total inbound call volume of 32,941 indicates a significant level of interaction with customers. Among the reasons for calls, "Billing Question" had the highest number of callers, followed by "Payment" and "Service Outage."

2. **Calls by Call Center Location:** The distribution of calls across different call center locations shows that "Baltimore/MD" received the highest number of calls, followed by "Los Angeles/CA," "Chicago/IL," and "Denver/CO."

3. **Calls by Channel:** The distribution of calls by channel indicates that the majority of calls were handled by the "Call-Center" channel, followed by "Chatbot," "Email," and "Web." This suggests that the call center is the primary communication channel for customers.

4. **Sentiment Analysis:** Analyzing customer sentiment, it is evident that there were a considerable number of "Negative" and "Very Negative" sentiments expressed by callers. "Neutral" and "Positive" sentiments were also observed, but to a lesser extent. Addressing negative sentiments could be crucial for improving customer satisfaction.

5. **Calls by Response Time:** The categorization of calls based on response time indicates that a significant number of calls were handled "Within SLA" (Service Level Agreement). However, there were still a notable number of calls categorized as "Above SLA." This suggests an opportunity to improve response times for these calls.

# Recommendations:

1. **Focus on Billing Questions:** Given the high volume of calls related to billing questions, consider streamlining and automating billing inquiries to reduce the load on the call center. Implement self-service options, or FAQs for common billing queries.

2. **Response Time Optimization:** Pay special attention to calls categorized as "Above SLA." Analyze the reasons for delays and take measures to improve response times. Efficiently handling these calls can enhance customer satisfaction.

3. **Sentiment Analysis:** Addressing negative sentiments is crucial. Identify the root causes of negative customer experiences, such as unresolved issues or lengthy wait times, and work on improving these aspects.

4. **Training and Empowerment:** Provide call center agents with adequate training and tools to handle customer inquiries effectively. Empower them with the knowledge and resources to resolve issues promptly.

5. **Channel Diversification:** Explore the possibility of diversifying communication channels further. Enhance the capabilities of the "Chatbot," and consider expanding the use of "Email" and "Web" channels for specific types of inquiries.

6. **Customer Education:** Educate customers about the available communication channels and self-service options to encourage the use of more efficient channels for certain types of inquiries.
















 



 


Next was to 
To change the channel Pivot table to a get percentage I changed 

 
The pics of the transpose 
  
 
My Pivot Table
 













 
