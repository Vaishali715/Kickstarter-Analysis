# Kickstarter-Analysis 

Performing analysis on Kickstarter data to help Louise visualize the relation between Campaign outcomes and the factors helping/affecting it.
## Overview of Project
This project helps Louise to study about her Campaigns with respect to the other factors, such as the Outcomes, Country, Goal amount, pledged amount, etc., and then figuring out possibly which Goal amount to be considered or which Country supports her Campaigns the best or which categories she should select.
### Purpose
The purpose of this analysis is to help Louise find out about how different campaigns are performing in relation to their launch dates and funding goals. Also to visualize the campaign outcomes based on their Launch Dates and Funding Goals.
## Analysis and Challenges
The analysis was done based on two Outcomes.
* Outcomes based on Launch Date ![TheaterOutcomes_LaunchDate.png] (This PC/C:/Users/vaish/Kickstarter-Analysis/Deliverable_1/Resources/TheaterOutcomes_LaunchDate.png)
* Outcomes based on Goals ![OutcomesBased_Goals.png] (This PC/C:/Users/vaish/Kickstarter-Analysis/Deliverable_2/Resources/OutcomesBased_Goals.png)
### Analysis of Outcomes Based on Launch Date
Here, the analysis is done using pivot tables and graphing. After creating a new column, labeled as "Year", the YEAR() function is used to extract the year from "Date Created Conversion" column. Then created a Pivot table and filtered the data based on "Parent Category" and "Years". After placing the pivot table fields in Rows, Columns and Values, the Row Labels were grouped to show only the months of the Year.

Then, I created a Line Chart from the Pivot Table which helps in visualizing the relationship between Outcomes and Launch Month.
### Analysis of Outcomes Based on Goals
Here, to carry out the analysis we are first creating a range of rows and columns, wherein the Goals column we are creating different Goal amount range which helps to group the projects based on their Goal amounts.

Then using the COUNTIF() and SUM() functions, all the rows and columns are populated with respect to the specified conditions. A line chart is created to visualize the relationship between the Goal amount ranges and the percentage of Successful, Failed and Canceled projects.
### Challenges and Difficulties Encountered
For Deliverable 1, I did not face any difficulty.

For Deliverable 2, in the Line Chart, the X-axis was showing serial numbers (starting from 1,2,3,4....) instead of the Goal column values. After looking up for all the options for Axis Data in Excel, I was able to change it. And the Y-axis was not showing the values as percentages. After changing the formula in Percentage column and settings in the Number field, the issue was resolved.
## Results
**What are two conclusions you can draw about Theater Outcomes by Launch Date?**
1. The highhest number of Kickstarter campaigns were recorded in the month of May and there was a significant drop in the month of December.
2. May, June, July and October have moreover same number of Failed Campaigns launched.

**What can you conclude about the Outcomes based on Goals?**
1. We can see that the "Percentage of Successful Campaigns" and the "Percentage of Failed Campaings" curves are mirror images of each other. That means considering the Goal Amount from "Less than 1000" to "Greater than 50000", over a range we can see that "Percentage of Successful Campaigns" start from Higher value and ends at lower value whereas "Percentage of Failed Campaings" start from Loer value and ends at Higher value.
2. The number of "Total Projects" are higher when the Funding Goal amount is low and as the range of Goal amount is increased, the number of "Total Projects" is decreased. It means the amount of money plays a major role in the successful campaigns.

**What are some limitations of this Dataset?**

**What are some other possible tables and/or graphs that we could create?**

Created two more possible tables 
