# Kickstarting with Excel

Report for the Berkley Data Analytics Bootcamp - Module 1 - Kickstarter Challenge 1 {Excel}

## Overview of Project
This Data project is for Louise who is an Upcomming Playwright who wants to start a crowdfunding campaign for her play “Fever”. She has collected information for the estimated budget of her play as well as crowdfunding data for similar crowdfunding campaigns and would like to get a greater understanding by looking at that data if there are any specific details that makes a campaign successful so she can set her campaign to mirror other successful campaigns in the same category. 

### Purpose
The dataset for various crowdfunding campaigns is tracked using several details like financial goals, pledges, launch dates, number of backers, average donations and if the campaign was successful or not. This information provided insight that there were certain campains that were successful while come failed. The idea behind creating this analysis is that the new organised dataset will tell her a story such that will assist in understanding what she can focus on to make her campaign successful. This dataset will focus on 2 definitive details – 1. Analysis of outcomes based on Launch Date and 2. Analysis of Outcomes based on Goals

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The dataset for various crowdfunding campaigns is tracked using several details like financial goals, pledges, launch dates, number of backers, average donations and if the campaign was successful or not. This information provided insight that there were certain campains that were successful while come failed. The idea behind creating this analysis is that the new organised dataset will tell her a story such that will assist in understanding what she can focus on to make her campaign successful. This dataset will focus on 2 definitive details – 1. Analysis of outcomes based on Launch Date and 2. Analysis of Outcomes based on Goals


### Analysis of Outcomes Based on Goals
In this we will present an analysis of outcomes of crowdfunding data based on Goals using the criteria of the percentage of successful, failed and cancelled “Plays”. To do this we first broke down the monetary value of the goal in ranges to see the data per section, most of the ranges are in increments of ~ $5000 with the exception of the first 2 ranges. In doing this we will compare the dollar value on X-axis and outcomes [successful, failed or cancelled] on Y-axis.
The represented data now shows that 84% of the plays have a goal of less than $10,000 also majority of successful plays {76%} have a fundraising goals of $4,999 or below. But if the fundraising goal is higher than $15000 there is a 50% chance to fail compared to 27% failure rates if the goal is below $5000. Interstingly there are no canceled campaigns in the plays subcategory.

### Challenges and Difficulties Encountered
Challenges in Analysis of outcomes based on Launch Date-Preparing the data was challenging in relation to the Pivot table where it was important to get an understanding of what data parameters should be placed where to get a appearance of the data visual aid [Line Graph] that can be understood with ease. For when adding date created if I wanted to just see the data organised by months I had to eliminate years from the rows.

Challenges in Analysis of Outcomes based on Goals - Is utilising the countif function and the correct criteria to get the necessary data populated, I required to focus on the necessary data and use the correct filters and terminology to get that right and it populated the information in my report.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1.	Theater Campaigns have peak success during the month of May and planning a campaign during that time should be explored by Louise
2.	Failure and success rates of plays go parallel to the latter part of the year particularly during the months of September thru December making it not the best time to launch a campaign.


- What can you conclude about the Outcomes based on Goals?
1.	84% of the Plays have a goal of less than $10,000.
2.	76% of the Plays with a fundraising goal of less than $1,000 were successful Vs 100 % plays with funding goal between 45000-49999 failed.
3.	Plays are more likely to fail {approximately 50% failure rate} if your fundraising goal is $15,000 and above


- What are some limitations of this dataset?
1.	There are several factors that have a role in the success of failure of any art that includes location in the country, population, socioeconomic factors, access to the theater, performance of actors, weather conditions, Health situations like an Epidemic or Pandemic and many others that can impact a data and hence there is a bias that cannot be ruled out when coming to a definitive conclusion to a success or failure
2.	This data is restricted to plays and theater, hence the focus of our outcomes is restricted to that section. Access to a broader platform is missing causing the final result to be viewed with a narrow or tunnel vision.
3.	 Is all the necessary data represented? Is all the data provided accurate? Is all the data that is collected truly essential in explaining the nature of success or failure?


- What are some other possible tables and/or graphs that we could create?
1.	A table of how long a campaign had been successful and measuring the success over that period can help identify when it would be a good time to continue or discontinue the campaign
2.	Having a chart of goal to pledged could help understand if there was enough funding available to start a campaign.


