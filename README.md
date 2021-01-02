# kickstater-analysis
## Performing analysis on Kick starter data to uncover trends 
I. **Overview of the Project**

The purpose of this analysis is to provide Louise with information at glance regarding the most popular and successful type of compaign,**Theater**. 
    
  1. **Purpose** 
     
So in order to help Louise with her fundraising Goal, and to fully have a better understanding on how the compaign fared in relation to the launched dates an funding Goal, we started by giving a visual charts that will help Louise have a representations of various compaign statistics regarding relevant categories to Louise's Project.

Data Source. [here](/kicktarter_Challenge.zip).

II. **Analysis and Challenges**

  - Deliverable 1:
     **Theater_Outcomes_vs_Launch_Date**
     
     ![Theater_Outcomes_vs_Launch](/Resources/Theater_Outcomes_vs_Launch.png).
   
      This chart helps to visualize Kickstarter compaign based on the Launched Date, to aknowledge the failure and success of each kisktarter compaign especially **theater**,
   Also to determine the month that launched the most successful kickstarter compaign.
   
   - Deliverable 2:
     **Outcomes_Based_on_Goals**
     
     ![Outcomes_vs_Goals](/Resources/Outcomes_vs_Goals.png).
     
     This chart helps to visualize the count number of successful, failed and canceled kickstarter compaign with the respect of the subcategory "plays", as well as the range of fundraising amount classified by range of fundrainsing amount goal starting from 0$ to greater than 50000$.
     In order to give a sense of scale, we divided the summation of all the counts based on goal range to calculate the percentage of successful, failed and canceled kicktarter compaign.
     
   - Challenges

     There were no challenges encountoured to provide the above visualizations. The potential challenge that occure is a missed/mis-typed data that could conduct to an error once trying to generate a chart. (Yet, we can notice for the first Deliverable that no data was reported regarding the canceled theater project for the month of October, but it didn't impact our chart).
Also, for the second Deliverable, inputting the COUNTIFS formula to each cell was time consuming that we can just avoid by using the CONCATENATE formula (shortcut &) to each range of fundraising.
   
3. **Results**
 
   - Two Conclusions about the Theater Outcomes based on Launched Date: The month that launched the most successful compaign was May and June.
 However the months of January, March and September all had roughly the same number of failed compaign launched.
   - Conclusion about the Outcomes based on Goals: the needed money range to have a successful compaign is between $1000 and $4999.
   - Limitations of data set 
