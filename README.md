# Kickstarter Analysis

Overview of Project: 

In this project, I'll be assisting a new up-and-coming playwright, Louise who is in the process of launching a crowdfunding campaign to help fund her play, Fever. The estimated budget for her play is $10,000. By performing data analysis on several thousand crowdfunding projects, I'll identify some trends and factors that will make crowdfunding project' campaign successful. And use the new 

Purpose:

The purpose of this analysis is to determine how different campaigns fared in relation to their launch dates and their funding goals. This will provide new information that will help Louise set her campaign to reflect other successful ones in the same field.

Analysis of Outcomes Based on Launch Date:

In this part of the analysis, my goal is to provide Louise the ability to visually process the campaign outcomes - successful, failed, and canceled against the launch date. To accomplish this result, I extracted a set of data from the larger Kickstarter file. I began by filtering Parent Category to select “Theater” and used the Year () function to select just the "Years" from the Date Created column. Then, I set my columns to be the outcomes and rows to be the Date Created Conversion showing only the month of the Launch Date. Based on this analysis, The Data concluded that there has been a total of 1369 theater campaigns. Among these 839(61%) were successful, 493 (36%) were failed, and 37 (3%) were cancelled.  By utilizing this data, I created a line chart "Theater Outcomes based on Launch Date" to showcase the relationship between the launch date (X) and outcome count (y). Understanding which months or season to launch Kickstarter will help Louise to plan her campaign accordingly. Based on this data, we can determine that successful theater campaigns were launched during late Spring/early Summer (May-June), while failed campaigns were launched in the Winter (December).

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/101952961/162645717-6266762d-249c-49b2-8a52-9065b715922b.png)

Analysis of Outcomes Based on Goals:

In part II of this analysis, my goal is to help Louise visualize the percentage of successful, failed, and canceled plays based on the funding goal amount. Similar to the previous analysis, I extracted a set of data from the larger Kickstarter file. Then, I created a table of the Funding Goal (dollar-amount ranges so that projects can be grouped based on their goal amount) and Outcomes. The Outcomes were grouped in Number of Successful, Failed, Canceled, and Total Projects. I used the COUNTIFS () function to collect the outcome and goal data for the “plays” subcategory. I then used the SUM () function to generate the Total Projects column and calculated the percentage by dividing the Number Successful, Failed, and Canceled by the Total Projects. Based on this analysis, Louise has a 54% chance of being successful and 46% chance of failing as her play budget is estimated to be $10,000.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/101952961/162645699-0be5f6e8-ce24-42f3-8df6-b1127fcb572f.png)

Challenges and Difficulties Encountered:

The major challenge I'd faced while completing this assignment was figuring out how 
to use the COUNTIFS () function and making sure I was putting the correct phrase in the syntax.

Results:

The Outcomes based on Launch Date analysis indicate that theater campaigns launched in
late Spring/early Summer (May-June) have a more successful outcome than those launched 
in the Winter (December). I would recommend for Louise's "Fever" play to be launched 
sometime late Spring/early Summer. Goals set less than $1,000 have a 76% success rate. Which indicates, the higher the goal, the risk of a failed campaign increases. Louise’s play, with a budget of 10,000, has a 54% chance of being successful and 46% chance of failing. In order to make a more definitive analysis, it is critical to understand factors that contributed to the failed outcomes. Although it is evident that warmer seasons produce successful outcomes. It is also important to understand why campaigns with increased goals tend to fail. Is it the length of the Kickstarter, marketing techniques or the country and play type? we can create another line graph to show the length of the campaign in relation to its Outcome.



