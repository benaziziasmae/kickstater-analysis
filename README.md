# kickstater-analysis
## Performing analysis on Kick starter data to uncover trends 
I. **Overview of the Project**

The purpose of this analysis is to provide Louise with information at glance regarding the most popular and successful type of compaign,**Theater**. 
    
   **Purpose** 
     
So in order to help Louise with her fundraising Goal, and to fully have a better understanding on how the compaign fared in relation to the launched dates and funding Goal, we started by giving a visual charts that will help Louise have a representations of various compaign statistics regarding relevant categories to Louise's Project.

Data Source. [here](/kicktarter_Challenge.zip).

II. **Analysis and Challenges**

  1. Deliverable 1:
     **Theater_Outcomes_vs_Launch_Date**
     
     ![Theater_Outcomes_vs_Launch](/Resources/Theater_Outcomes_vs_Launch.png).
   
      This chart helps to visualize Kickstarter compaign based on the Launched Date, to aknowledge the failure and success of each kisktarter compaign especially **theater**,
   Also to determine the month that launched the most successful kickstarter compaign.
   
   2. Deliverable 2:
     **Outcomes_Based_on_Goals**
     
   ![Outcomes_vs_Goals](/Resources/Outcomes_vs_Goals.png).
     
   This chart helps to visualize the count number of successful, failed and canceled kickstarter compaign with the respect of the subcategory "plays", as well as the range of fundraising amount classified by range of fundrainsing amount goal starting from 0$ to greater than 50000$.
     In order to give a sense of scale, we divided the summation of all the counts based on goal range to calculate the percentage of successful, failed and canceled kicktarter compaign.
     
   3. Challenges

   There were no challenges encountoured to provide the above visualizations. The potential challenge that can occure is a missed/mis-typed data that could conduct to an error once trying to generate a chart. (Yet, we can notice for the first Deliverable that no data was reported regarding the canceled theater project for the month of October, but it didn't impact our chart, it only gives a discountinued line).
Also, for the second Deliverable, inputting the COUNTIFS formula to each cell was time consuming that we can just avoid by using the CONCATENATE formula (shortcut &) to each range of fundraising.
   
  III. **Results**
 
   1. Two Conclusions about the Theater Outcomes based on Launched Date: 
   
   The first conclusion that can be drawn based on the data is that the month that launched the most successful compaign was May.
   
   The second conclusion is that the months of January and March all had roughly the same number of failed compaign launched.
   
   2. Conclusion about the Outcomes based on Goals:
   
   From the chart above, we can conclude that the chance of having a successful compaign goes simultaneously with a lower range of fundraising amount.
   The other conclusion that can be drawn from the data is that for the range between 15000$ and 19999$ we had a percentage of 50% for both failed and successful compaign, and for the range of 45000$ to 49999$ we had a percentage of 0% for successful compaign and 100% for failed compaign wich does not give a clear idea about the relationship between a successfulanf failed compaign.
   
   3. Recommendation for additional tables or graphs 
   
   Based on the analysis that we did previously with the Theater Outcomes based on Launch_Date, we can go a further deeper in our analysis by doing an additional filter on the pivot table by choosing **plays** as *Subcategory*, in order to provide another revelation that May and June both have a highest susccess for launching a kickstarter as provided below.
   
 ![Theater_Plays_Outcomes_vs_Launch_Date.png](/Resources/Theater_Plays_Outcomes_vs_Launch_Date.png).
 
 
