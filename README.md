# US_Call_Center_Dashboard                                              

## Table of Contents

- [Project Overview](#project-overview)
- [Requirements](#requirements)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Pipeline](#data-pipeline)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Summary of Findings](#summary-of-findings)
- [Results from Findings](#results-from-findings)
- [Recommendations](#recommendations)

![summary](https://github.com/KHard2Bme/US_Call_Center_Dashboard/assets/146769989/6ff2ab9b-acf1-4423-adf9-4d093e6a2a44)

![baltimore](https://github.com/KHard2Bme/US_Call_Center_Dashboard/assets/146769989/624c650f-fd49-4dbc-bd93-8fbd3bf84a7a)

![chicago](https://github.com/KHard2Bme/US_Call_Center_Dashboard/assets/146769989/8cdce0d8-66b2-46f3-90d9-2e532dbdca37)

![denver](https://github.com/KHard2Bme/US_Call_Center_Dashboard/assets/146769989/da371871-1b0a-42b9-b184-d5a10651484e)

![losangeles](https://github.com/KHard2Bme/US_Call_Center_Dashboard/assets/146769989/9058d497-58f9-47ab-b9c9-ba97c9aa3eef)


### Project Overview
---

This data analysis project aims to provide insights into the performance of each call center over a one year period. By analyzing various aspects of the data, we seek to identify trends, make data-driven recommendations, and gain a deeper understanding of the company's performance.





### Requirements
---

Client wants to create a call center dashboard for year 2020 so that they can have insight on the below requirements.

- Primary KPI: Total inbound calls by call centers within the United States

         Total inbound calls by channel:
             - Call center  
             - Chatbot  
             - Email
             - Web

              
- Secondary KPI:  

              -  Report showing breakdown of inbound calls by call center  
              .  Report showing breakdown of inbound calls by sentiment.  
              -  Column chart showing breakdown of reason by sentiment.  
              -  Column chart showing breakdown of response time by call center. 
              -  Chart showing total count by reason of call
               - Grid view dashboard allowing stakeholders to search for granular information in dataset and  download if needed



### Data Sources
---

Call Center Data: The primary dataset used for this analysis is the "Call_Center.csv" file obtained from Kaggle which contains fictitious data.


### Tools
---

- Excel - Data Cleaning, processing, analysis, report and dashboard creation.



      
## Data Pipeline
---

### 1. Data Cleaning

Data loading and inspection:
- Checking column header and rows for correct spelling, null values, extra spaces, datatypes and duplicates.

### 2. Data Processing
 
 Creation of customized columns utilizing the DAY(), WEEKEND(), and IF() formulas. 

### 3. Data Analysis 

Creation of Pivot tables, basic and customized charts while using IFERROR() formula to resolve #REF errors.

### 4. Report/Dashboard

Building of the dashboard as well as adding charts and slicers. 
 


### Exploratory Data Analysis
---
Questions the client has that can now be answered.

1. What is the total number of inbound calls received by call centers for the year 2020? By channel? By weekday and weekend?

2. What is the average call duration for all inbound calls for the year 2020? Minimum and Maximum duration?

3. Which call center received the most inbound calls during the year 2020? The least inbound calls?
 
4. Which sentiment ranks the highest amongst all inbound calls in 2020? Highest also by which reason type?
 
5. For Los Angeles, the sentiment that ranks the highest is negative which amounts to about 34% of total inbound calls; 4,601 calls out of 13,734. Billing questions is the reason type having the majority.
 
    - What 5 states and cities contain the highest number of callers who gave a negative sentiment within reason type billing questions?

6. Denver CO is the call center that has received the least number of inbound calls in comparison to the others; roughly 8% of 2,776 calls. The sentiment that ranks the highest is also negative, which amounts for about 33% of total inbound calls; 912 calls out of 2,776. Billing questions is the reason type having the majority.

     - What 5 states and cities contain the highest number of callers who gave a negative sentiment within reason type billing questions?
 
7. In regard to response time by call center; below/within/above SLA, below SLA accounts for 25% of all inbound calls.

    The Los Angeles call center has the highest number of inbound calls which fall below SLA; 3,327 calls at 41%.
   
     -	Which calls fall below SLA by channel? By weekday and weekend?
     -	Which calls have a duration of 5 min? 
     -	Which calls have a duration of 45min? 
     -	Which calls have an average duration of 25 min?

8. The Baltimore MD call center has the second highest number of inbound calls which fall below SLA; 2,768 of calls at 34%.
 
   -	Which calls fall below SLA by channel? By weekday and weekend?
   -	Which calls have a duration of 5 min? 
   -	Which calls have a duration of 45min? 
   -	Which calls have an average duration of 25 min? 




## Summary of Findings
1.
   -  The total number of inbound calls received by all call centers for the year 2020 is 32,941.
   -  By channel there are 19,639 received within Call Centers, 8,356 within Chatbots, 7,470 within emails and 6,576 on the web.
   -  The total number of inbound calls received during the week is 23,073 while those received during the weekend are 9,866.
  
2. The average call duration is 25 minutes, the minimum is 5 minutes while the maximum call duration is 45 minutes.


3.  - Los Angeles call center received 13,734 inbound calls during the year 2020: about 42%.

    - Denver call center received 2,776 inbound calls during the year 2020: about 8%.
 
4.
   -  Wednesday, October 21 received 1,170 inbound calls in the year 2020. The total call duration was 28,994 minutes (483 hours) and the average call duration 
       was 25 minutes.
   -   Friday, October 31 received only 1 call in year 2020. The call was received at the Chicago IL call center from a Sashenka Cauley who called in from 
       Sacramento Ca. The call sentiment was very positive and the reason for call being billing question. The call duration was 13 minutes.  
     
 
5. 
    - States: California 370, Texas 365, Florida 266 and New York 169
    - Cities: Washington 111, Houston 74, New York city 53, Dallas 52 and Atlanta 45

6.
   - States: California 73, Florida 65, New York 33, Ohio 25 and District of Columbia 24
   - Cities: Washington 24, El Paso 13, Houston 13, Dallas 12 and Birmingham 9

7.  
    - By channel we have: Call center 1092, Chatbot 840, email 737 and web 658
    - There are 759 inbound calls on weekday and 333 inbound calls by weekend.
    - 87 calls have a duration of 5 minutes
    - 82 calls have a duration of 45 minutes
    - 86 calls have an average duration of 25 minutes

8.    
    - By channel we have: Call center 902, Chatbot 674, email 604 and web588
    - There are 637 inbound calls on weekday and 265 inbound calls by weekend.
    -	 71 calls have a duration of 5 minutes
    -	 61 calls have a duration of 45 minutes
    -	 64 calls have an average duration of 25 minutes




### Results from Findings

The analysis results are summarized as follows:

1.  A large percentage of inbound calls fall within the negative sentiment category, making up roughly 34% of total calls. Of those calls 71% fall within the billing questions reason type, followed by 14% in payments.  
  This is also true within every call center, having a large percentage of the calls falling within the negative sentiment category as well.

2.  Regarding call response time, a large percentage of the total inbound calls fall within the SLA; 63%, but 25% of the calls are below the SLA.
  
3. There seems to be a correlation between calls that have a negative sentiment and those falling below the SLA. Most of the calls come in through the call center channel on weekdays, and the reason type is either billing questions or payment. This is the case for all call centers.

### Recommendations

Based on the analysis, we recommend the following actions:

In order to find out the exact issue at hand we will need to first retrieve the audio recordings of each agent who picked up a call at designated call time stamp. We need to listen to each call and determine.

   - was call picked up and placed in queue
   - how long was the customer waiting in queue/did they hang up while waiting
   - did the agent answer all questions correctly and appropriately
   - was the customer satisfied with answer, if not what were next steps
   - was customer transferred to another Department or Manager for assistance and did that call go through successfully
   - were questions answered after being transferred.

Once we gather enough data, research the findings and try to understand the trends we can then come to a conclusion as to what the root cause or causes are.


