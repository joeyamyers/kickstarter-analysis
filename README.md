# kickstarter-analysis
Performing analysis on Kickstarter data to uncover trends for future successful kickstarters
# Kickstarting with Excel

## Overview of Project


### Purpose
The goal of this analysis is to help playwright, Louise, with her crowdfunding campaign on Kickstarter. The insights derived from the data of 4000+ Kickstarter campaigns will be used to coordinate Louise's own Kickstarter campaign in giving her the best chance for success. Aspects including a campaign's launch date and fundraising goal were identified as potential factors of successful campaigns and will shape the parameters of Louise's Kickstarter.  Additionally, the analysis will help Louise gain a better understanding of the successful aspects of comparable projects that she can then apply to her own project.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/96351306/148727385-2af25cbc-90a0-4a20-adb7-e397e988777c.png)

Pivot tables and charts were utilized to determine whether a campaign's launch date (month) had any bearing on its outcome. There were three possible outcomes for a Kickstarter campaign: successful, failed, or canceled. I started by subsetting the dataset into a pivot table and then filtered the pivot table to only show the "theater" parent category to compile projects most similar to Louise's. Each theater Kickstarter was then organized by its outcome and according to which month the campaign began.

I created a chart (seen above) in order help visualize the findings from the pivot chart. With each month of the year as the X-axis and the agggregated count of each outcome on the Y-axis, the chart made it apparent which months were most and least successful based on launch date.

### Analysis of Outcomes Based on Goals

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/96351306/148727507-c0c2d531-fae3-41e8-895f-ecdb5b5924c3.png)

Finding the outcome of Kickstarter projects based on goals was very similar to the process of finding the outcomes based on launch date. Each project was placed into one of twelve goal ranges based on its own campaign goal. The projects were then counted respective to its goal range and on the outcome (successful, failed, or canceled). The projects per goal range were totaled to find the rate at which each project was successful, failed, or canceled. 

These findings were easier understoood by the chart above. I created a line graph showing the trends of each outcome with the goal outcome ranges as the X-axis  and the outcome percentages as the Y-axis. The graph made it clear to see that as the goal ranges increased, the success rates declined.

### Challenges and Difficulties Encountered

This analysis ran smoothly, but I believe that without visualizing the data through line graphs, these uncovered trends would be much more difficult to discover. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Based on the data, I determined that May and June are the optimal months for launch dates for theater kickstarters. These two months have compiled more successful Kickstarter campaigns than other months. I also found that the worst time period to launch a theater kickstarter is nearing the end of the calendar year as November and December totaled the least amount of successful projects.

- What can you conclude about the Outcomes based on Goals?
I found there to be a general inverse relationship between success rate and the Kickstarter goal amount. The data showed that as the goal amount ($) increased, the percentage of successful Kickstarters declined. Additionally, larger projects aiming to raise more than $50,000 failed almost 60% of the time. Louise's estimated goal of $12,000 placed her in the goal range with a 48% succesful outcome based on this data.

- What are some limitations of this dataset?
The lack of descriptive data stands out as a significant limitation in this dataset. More descriptive data in relation to outcomes (ie. intended age group, age of backers, genre) would have been more advantageous for Louise's overall marketing strategy and future Kickstarters. Additionally, more data specifically for the theater parent category and play subcategory would be helpful in performing a more accurate and specific analysis for Louise's Kickstarter.

- What are some other possible tables and/or graphs that we could create?
It would have been advantageous to visualize the potential correlation between the Kickstarter outcome and the amount of the days the campaigns lasted. This relationship would be beneficial for Louise's marketing strategy.
