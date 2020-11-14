# Kickstarter Campaign Analysis

### Purpose
 There are thousands of Kickstarters and Louise wants to know how successful Kickstarters are based on their launch date and goal. 
  
### Analysis of Outcomes Based on Launch Date
![Theather Outcomes vs Lauch](https://github.com/AmirO8/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

   From May 2009 to January 2017 there were 1369 theather Kickstarters. Of those 1369, 839 were successful, 493 failed and 37 were canceled. The month of May had the most total successful Kickstarters at 111 and the month of December had the least total successful Kickstarters. However the total number of created Kickstarters for each month varied with May having the most and December having the least. 
   Even though there are many Kickstarters started in May that is when I would recommend starting one. May had the best percentage rate of success followed by June. There are not many Kickstarters launched in December. When they are, they less than 50% are successful. To obtain these numbers I used the [COUNTIFS](https://support.microsoft.com/en-us/office/countifs-function-dda3dc6e-f74e-4aee-88bc-aa8c2a866842), [SUM](https://support.microsoft.com/en-us/office/sum-function-043e1c7d-7726-4e80-8f32-07b23e057f89), & [ROUND](https://support.microsoft.com/en-us/office/round-function-c018c5d8-40fb-4053-90b1-b3e7f61a213c) functions.

### Analysis of Outcomes Based on Goals
![Theather Outcomes Based on Goals](https://github.com/AmirO8/kickstarter-analysis/blob/main/Resources/Outcomes%20Based%20on%20Goals.png)

  The most common goal total for a Kickstarter is between 1,000 and 4,999, they yield the most successful Kickstarters. However when we take a look at the percentage of the Kickstarters that are successful the ones that request less than 1,000 are the most successful at 75.81%. An interesting point on the line graph is that there were no canceled Kickstarters in October.

### Challenges and Difficulties Encountered
 Making sure my tables and graphs were accurate were the most important aspect. The outcomes based on lauch date was pinpoint because I had a table to compare my work to. The outcomes based on goals was challenging because on my first attempt my line chart was not the same as the module. My mistake was able to be corrected once I cleared the sorting, formating, and compared it to the original data set. 

## Results
   In my analysis below I will discuss how the results of successful Kickstarter plays. Lauching a Kickstarter in December doesn't yield a good success rate. Lauching a Kickstarter in May yields the highest success rate for a Kickstarter. A Kickstartrer with a goal between 1,000 and 4,999 are the most successful. This can be a challenge for Kickstarters that need more funding. Kickstarters that needed 50,000 or more in funding failed at a whopping 87.5%.
   
   As for the limitations there is one item I would like to know about are there multiple people/groups who created Kickstarters on this data set. From this we can see if they are successful creator on Kickstarter. The last Kickstarter on our data set is in 2017 this is not current for Louise as we are in 2020. 
   I was curious as to the count of days a Kickstarter was active and their success rate. To do this I can create another table using [COUNTIFS](https://support.microsoft.com/en-us/office/countifs-function-dda3dc6e-f74e-4aee-88bc-aa8c2a866842) but this time we use days the Kickstarter was active. To do this I subtracted date ended and date created. The range for the Kickstarter days was 1 - 90, I used table similar to the Outcomes based on goals as follows 1-10, 11-20, e.t.c. I found that the most successful Kickstarters had between 21-30 days to be funded.  

