![INTRO](https://user-images.githubusercontent.com/84449238/182936181-b1dc651b-3bdc-4a49-b6c3-c337668ba4ed.JPG)
# Predict Click Through Rate (CTR) of an Email Campaign

**1) Problem Statement:-**


Most organizations today rely on email campaigns for effective communication with users. Email communication is one of the popular ways to pitch products to users and build trustworthy relationships with them.


Email campaigns contain different types of CTA (Call To Action). The ultimate goal of email campaigns is to maximize the Click Through Rate (CTR).


CTR is a measure of success for email campaigns. The higher the click rate, the better your email marketing campaign is. CTR is calculated by the no. of users who clicked on at least one of the CTA divided by the total no. of users the email was delivered to.


CTR =   No. of users who clicked on at least one of the CTA / No. of emails delivered


CTR depends on multiple factors like design, content, personalization, etc. 


How do you design the email content effectively?
What should your subject line look like?
What should be the length of the email?
Do you need images in your email template?

As a part of the Data Science team, in this hackathon, you will build a smart system to predict the CTR for email campaigns and therefore identify the critical factors that will help the marketing team to maximize the CTR.
Objective


Your task at hand is to build a machine learning-based approach to predict the CTR of an email campaign.



**2) About the Dataset:-**


You are provided with the information of past email campaigns containing the email attributes like subject and body length, no. of CTA, date and time of an email, type of the audience, whether its a personalized email or not, etc and the target variable indicating the CTR of the email campaign.

**2.1) Data Dictionary:-**

You are provided with 3 files - train.csv, test.csv and sample_submission.csv

**2.1.1) Train and Test Set:-**


Train and Test set contains different sets of email campaigns containing information about the email campaign. Train set includes the target variable click_rate and you need to predict the click_rate of an email campaign in the test set.

![IMAGE1](https://user-images.githubusercontent.com/84449238/182934341-95f5c2f5-24ee-4c6c-be8f-8b37ad89da3c.JPG)

![IMAGE2](https://user-images.githubusercontent.com/84449238/182934368-bf1b63a6-c4c0-45c0-b2a8-84706e0e0fdb.JPG)

**2.1.2) Submission File Format**

![IMAGE3](https://user-images.githubusercontent.com/84449238/182934572-bda14b09-0cb7-4be4-a67d-7e0875af13a4.JPG)

**3) Evaluation metric:-**
The evaluation metric for this hackathon would be r2_score.



Public and Private Split

Test data is further divided into Public (40%) and Private (60%) data. Your initial responses will be checked and scored on the Public data. The final rankings would be based on your private score which will be published once the competition is over.

sample_submission.csv contains 2 variables - campaign id and click_rate
# How does JOB-A-THON work?
![AV-Image-31072022](https://user-images.githubusercontent.com/84449238/182031346-653fd336-361c-4d2a-91b6-6941c5f57171.JPG)

