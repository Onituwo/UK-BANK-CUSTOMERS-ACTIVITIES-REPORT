## UK BANK AND THE ACTIVITIES OF ALL CUSTOMERS REPORTS 

## Introduction
This project is used for the insights generated from the dataset in order to improve the financial institution (UK Bank) in making data driven decisions for subsequent years and offering strategic recommentions purposely for driving more businesses and revenue generations.


## Problem Statement
The financial institution (UK Bank) in their first year of operations (2015) have hereby consulted me in the early year of 2016 with the sole aim of  carrying out a quick analysis and report. This is due to the fact that their stakeholders wish to build an Headquater office in the location/region with the highest number of customers. They also wish to know the month in which the highest number of customers enrolled into their financial institution. And also at the opening event of the newly built Headquater, the stakeholders wish to award Top 10 customers with the highest Balance in their respective bank accounts and to know those customers that are eligible to access loans from the Bank.

- After thinking critically, four questions are needed to be answered;
1. Total Customers By Region
2. Total Customers enrolled Per Month 
3. Top 10 Customers By highest account Balances
4. Loan Eligibilities for qualified customers
5. Other Relivants Insight

## Data source And Tools Used

- The dataset was gotten from Quantum Analytics NG and the dataset contains 10 columns and 4,014 rows.- 
- Dataset was locally extracted from Excel workbook into Tableau for analysis and visualization

## Data Transformation
### Using Excel;

- Downloaded the dataset as csv file, then open it on Excel and make it as a table.
- Then i had to change the column, Date Joined into English (United kingdom) format, so as to be able to work within the date time of the location of the financial institution.
- Since the dataset contains only one year (2015), i will be working with months in my analysis.

![](Date_enrolled2.PNG)

 - Then saved the dataset as an Excel file and upload it into Tableau for futher analysis and visualization.

### Using Tableau;

- I generated the following KPIs using calculated field
1. _Total Customers_ = count [customer_ID]
2. _Total Male Customers_ = IF[Gender] = "Male" THEN 1 ELSE 0 END
3.  _Total Female Customers_ = IF[Gender] = "Female" THEN 1 ELSE 0 END
4.  _Total Region_ = count [region]

## Explorating Data Analysis And Visualization

1. I created my first worksheet by using a Tree map chart, which shows the total customers from each of the locations/regions where the financial institution is domiciled.

  ![](Customers_by_region.PNG)

 - From this chart, we can see that England have the highest number of customers(2,159)

2. Then i created a line chart showing the total number of customers that enrolled into the Bank per month.
 
     ![](Customer_by_month.PNG)

 - From the chart, we can also see that it's in the month of October that the highest number of customers (545) enrolled into the Bank.

3. I then showed the Top 10 customers by Balance using horizontal bar chart
 
     ![](Top10_customers_by_balance.PNG)

 - Jason followed by Adam,Yvonne,Blake,Alan,Paul,Dominic,Boris,David and Connor are the customers that have the highest Balances in their respective bank accounts amongst the customers in descending order.
    
  4. Then, as required by the stakeholder of the Bank, in addition with the set-aside conditions for loan eligibility by the management of the Bank(Customers with more than 50,000 pounds in there bank accounts). I used table to load all the Customer_ID, Customers Name and created a calculated field to generate Loan Eligibilities. Then i added shape to tick-mark ✔️ those that are eligible and tick-cancelled ❎ those that are not eligible.
 
     ![](Loan_eligibility.PNG)

     **_You can interact with the dashboard Here_** (https://public.tableau.com/views/ABDULGANIYURIDWANONITUWOUKBANKCUSTOMERSASS/Dashboard2?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link).

 ## Conclusion
 
  Conclusively, these are the insights that can be gotten from my analysis, there are other relevant insights generated from my analysis such as;
     
  - Total Number of Regions = 4.
  - Total Number of Customers = 4,014.
  - Total Number of Male Customers = 2,165.
  - Total Number of Female customers = 1,849.
- The total bank account Balances by each of the 12 Months and
  - Customers by Job Classifications.
     
## Recommendations
  - England is the appropriate location to build the Headquater office.
  - The Top 10 Customers by Balance should be compensated and considered for accessing the bank loan facility.
  - The total number of customers that joined in the beginning of the year was quite minimal compared to those that joined towards the end of the year. Therefore, the stakeholders have to collaborate with the media department in order to create more awareness for those months with considerably low customers enrollment.


    **_Thank you_** 😃
