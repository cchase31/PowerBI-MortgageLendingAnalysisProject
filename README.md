Mortgage Lending Analysis

Project Overview: 
	This is a power bi project that demonstrates my skills at using power bi to do data and business analysis while also showing my understanding for identifying key information and trends that could be used to improve the business. 

Business Problem:
	The fictional business has experienced changes in application volume and lending performance over the past three years, They want a Power BI solution that can help them understand the application trends, applicant risk traits, interest rates, loan products, and operational processes that all affect lending performance. 

Dataset:
	This dataset was a fictional dataset created to simulate real mortgage applications and all of the factors that go into deciding whether a loan is going to be considered or not.

Data Preparation:
	Ensured all of the data was cleaned by checking the formatting for each column before modeling

Data Model:
	Created a date table, Created a ApplicationFacts table that was then able to be used to create a star schema with other tables. 

DAX Measures: 
	Created core DAX measures such as total applications, total funded amount and approval rate which are used multiple times throughout the analysis as tentpoles to see how other factors impact and change the levels for which these are implemented. 
	Created time intelligence to allow us to monitor how these factors have changed based on the date in which they were submitted, the day in which the processing was done, and the closing date. 
	Created calculated categories to allow for more simple grouping of data. This allowed me to make graphics that were easier to read and gain a better understanding of overall trends. 

Dashboard Pages:
Executive Summary:
Used to allow the viewer to gain an overall understanding of the state of the business over the last 3 years. Also lets the viewer see the base statistics we are going to be analyzing against different factors throughout the rest of the project
Application Funnel and Outcomes:
This is used to see how many of the applications that were submitted were actually approved and funded. This page also shows us how different types of loan products performed, what channels were getting the most applications and what states were getting the most funding
Applicant risk profile:
This page allows us to see what factors impacted approval rate the most, we checked the most common factors such as credit score, Debt to income, loan to volume and we decided to also check employment type.
Operating and Processing:
This is where we see if the internal processes of the mortgage company are having any significant affects on application submissions. We check to see how much the total and average amount of processing days has changed over the past 3 years while also observing how different loan products impacted our overall production
Loan Portfolio:
This is a page dedicated to an overview of the entire business over the last 3 years. It allows us to see how the different types of loan purposes and property types make up our entire portfolio of loan applications. This page focuses on general product stats rather than the stats of the customers who are applying for the loans
Interest Rates and Market Trends:
This page is dedicated to seeing how interest rates and the changed in them over time have impacted total applications, we use multiple different charts to see how interest rates have changed compared to the total applications we received during that same time. We also check to see if different types of loans have different interest rates and if that could affect applications. 
Data Quality:
This page is dedicated to making sure that the data we use in this data set can be considered accurate while also not allowing outliers to impact the quality of 
our analysis. 

Key Findings: 
Approval performance declined in 2024 and that coincided with the highest interest rates of 7%
Applicant risk characteristics had the strongest relationship with approval
Operational performance varies by channel and loan product
