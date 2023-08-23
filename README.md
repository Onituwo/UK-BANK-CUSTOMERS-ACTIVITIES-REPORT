## UK BANK CUSTOMERS ACTIVITIES REPORT 

## Introduction
This project, is to use the insights generated from the dataset to improve this financial institution (UK Bank) in making data driven decision for subsequent years,  and offering strategies,ultimately for driving more business and revenue generations.


## Problem Statement
The financial institutions (UK Bank) in there first year(2015) of operations have hereby consulted me in the early year of (2016) with carrying out a quick analysis and report, because there stakeholders wishes to build an Headquater office in the location/region with the highest number of customers. They also wish to know the month in which the highest number of customers enrolled into there financial institution. And also at the opening event of the new built Headquater, the stakeholders wishes to award Top 10 customers with the highest Balance in there respectives account and to know those customers that are eligible to access loan from the Bank.

- After thinking critically, four questions needed an answers
1. Total Customers By Region
2. Total Customers Joined Per Month 
3. Top 10 Customers By Balance
4. Loan Eligibility
5. Other Relivants Insight

## Data source And Tools Useed

- The dataset was gotten from Quantum Analytics NG and the dataset contains 10 columns and 4,014 rows.- 
- Dataset was locally extracted from Excel workbook into Tableau for analysis and visualization

## Data Transformation
### Using Excel;

- Downloaded the dataset as csv file, then open it on Excel, then make it as a table.
- Then i had to change the column Date Jioned into English (United kingdom) format, so as to be able to work within the datetime of the location of the financial institution.
- Since the dataset contains only one year 2015, i will be working with months in my analysis.

![](Date_enrolled2.PNG)

 - Then saved the dataset as an Excel file and upload it into Tableau for futher analysis and visualization.

### Using Tableau;

- I generated the following KPI's using calculated field
1. _Total Customers_ = count [customer_ID]
2. _Total Male Customers_ = IF[Gender] = "Male" THEN 1 ELSE 0 END
3.  _Total Female Customers_ = IF[Gender] = "Female" THEN 1 ELSE 0 END
4.  _Total Region_ = count [region]

## Explorating Data Analysis And Visualization

1. I created my first worksheet by using a Tree maps, which shows the total customers from each regions

  ![](Customers_by_region.PNG)

 - From this chart,we can see that England have the highest number of customers(2,159)

2. Then i created a lines chart showing the total numbers of customers that enrolled into the Bank per month.
 
     ![](Customer_by_month.PNG)

 - From the chart, we can see that it's in the month of October that the highest number of customers (545) enrolled into the Bank.

3. I then showed the Top 10 customers by Balance using horizontal bar chart
 
     ![](Top10_customers_by_balance.PNG)

 - Jason followed by Adam,Yvonne,Blake,Alan,Paul,Dominic,Boris,David and Connor are the customers that have the highest Balance in their respective account amongst the customers in descending order.
    
  4. Then, as required by the stakeholder of the Bank, couple with the set-aside conditions for loan eligibility by the management of the Bank(Customers with more than 50,000 pounds in there bank account). I used table to load all the Customer_ID, Customers Name and created a calculate field to generate Loan Eligible. Then added shape to tick-mark ✔️ those that are eligible and tick-cancelled ❎ those that are not eligible.
 
     ![](Loan_eligibility.PNG)

     **_You can interact with the dashboard Here_** (https://public.tableau.com/views/ABDULGANIYURIDWANONITUWOUKBANKCUSTOMERSASS/Dashboard2?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link).

 ## Conclusion
 
  Overall, these are the insights that can be gotten from my analysis, there are other relevant insights generated from my analysis such as;
     
  - Total Number of Region = 4.
  - Total Number of Customers = 4,014.
  - Total Number of Male Customers = 2,165.
  - Total Number of Female customers = 1,849.
  - Then Balance by Months and
  - Customers by Job Classifications.
     
## Recommendations
  - England is the appropriate location to build the Headquater office.
  - The Top 10 Customers by Balance should be compensated by award and considerable accessibility to multiple loans.
  - The total number of customers that joined in the bigining of the year was small compared to those that joined towards the end of the year, therefore the stakeholders have to collaborate with the media department in order to create more awareness for those months with considerably low customers enrollment.


     Thank you 😃
