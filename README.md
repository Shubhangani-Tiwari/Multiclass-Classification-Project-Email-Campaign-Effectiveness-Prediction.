# Muliclass-Classification-Project-Email-Campaign-Effectiveness-Prediction.
_______________
Project Type - Supervised ML Classification
______________
Contribution - Individual


# Problem Statement and Project Description
__________________
Small to medium business owners are using Gmail-based email marketing strategies to convert prospective customers into leads, but they are unable to track which emails are being ignored, read, or acknowledged by the reader. They want to create a machine learning model to help characterize and track these emails. The main objective is to improve the effectiveness of their email marketing efforts and increase customer retention.

# Variables Description:
______________________
Email_Id - Email id of customer

Email_Type - Email type contains 2 categories 1 and 2. We can assume that the types are like promotional email or sales email.

Subject_Hotness_Score - It is the email's subject's score on the basis of how good and effective the content is.

Email_Source_Type - It represents the source of the email like sales,marketing or product type email.

Email_Campaign_Type - The campaign type of the email.

Customer_Location - Categorical data which explains the different demographic location of the customers.

Total_Past_Communications - This columns contains the total previous mails from the same source.

Time_Email_sent_Category - It has 3 categories: 1,2 and 3 which are considered as morning,evening and night time slot.

Word_Count - Total count of word in each email

Total_links - Total number of links in the email

Total_Images - Total Number of images in the email

Email_Status - Our target variable which contains whether the mail was ignored, read, acknowledged by the reader


# 💾 Project Files Description:
_________________
This project contains one executable file: 
Classification_Project_Email_Campaign.ipynb:Complete Google Collab notebook containing data summary, exploration, visualisations, modeling, evaluation, conclusion and recommendations.
_____

# 📈 Exploratory Data Analysis:
_
In the Email Campaign Type feature, it seems like in campaign type 1 very few emails were sent but has a very high likelihood of getting read. Most emails were sent under email campaign type 2 and most ignored. Seems like campaign 3 was a success as even when less number of emails were sent under campaign 3, more emails were read and acknowledged.

Analyzing total past communications, we can see that the more the number of previous emails, the more it leads to read and acknowledged emails. This is just about making connection with your customers.

The more the words in an email, the more it has a tendency it has to get ignored. Too lengthy emails are getting ignored.

