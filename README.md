# kickstarter-analysis
Module 1 Kickstarter Challenge


## Overview of Project
The goal of the project was to help Louise determine which campaign project can help her raise enough money to put on her play Fever. Utilizing the skills we learned in module 1, we can help figure out which campaign would be the most effective for her to use to raise over $10,000. Some of the skills I used to sort through this large data set were Pivot tables, basic excel functions [SUM(), YEARS(), COUNTIFS()], etc., and  using the graphing feature and filtering and freezing panes. 

We created a pivot table to analyze the successful, failed, and canceled theater projects by month and year. From that pivot table we were able to see how many campaigns were successful/failed/canceled per month. We took those findings and graphed them so we could see how each outcome looked month by month.  If we wanted to see how another campaigns categories’ outcomes looked, we could use the filtering feature and swap out “theater” for another category, say “film & video”. See screenshot below to see how the pivot table changes when we filter to "film & video". We could then use the line graph to see how the outcomes looked for that campaign to see if that would be a better route for Louise to take to help raise money. 

<img width="373" alt="film_video" src="https://user-images.githubusercontent.com/45208773/131188527-9b9a65e0-d825-4c1d-9d3f-fa0042066a67.PNG">


We sorted through each month of theater campaigns to find the total of campaigns, how many campaigns were successful, failed and/or canceled. We created a chart and used the COUNTIFS() function to figure those numbers out. [insert goals & totals]. We then used the formula to find the percentage of each outcome by dividing the outcome from total and multiplying it by 100. 

<img width="241" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/45208773/131188297-a9903cd8-1d3e-41bf-928d-e9d8d626e5ab.png">


### Challenges and Difficulties Encountered
One of the challenges I encountered was trying to figure out the number of canceled projects. When I input the function into excel it gave me a “0” for every row. I was analyzing the function and comparing the function I had input to the “successful” and “failed” rows cells and it kept giving me 0. I thought I was doing something wrong. After thoroughly reviewing my functions, I was not able to find any mistakes or typos in my function. At that point, I went to the Kickstarter data set and filter it out to “plays” and “canceled” and noticed there were no plays that were canceled so my functions were correct. 

<img width="657" alt="challenges" src="https://user-images.githubusercontent.com/45208773/131188312-47ecff77-5921-4ee9-9c8c-d2d462581ad7.PNG">


## Results

### Analysis of Outcomes Based on Goals
**What are two conclusions you can draw about the Outcomes based on Launch Date?**

1. From the pivot table and graph created, I can conclude that May and June were the most successful months over the years for the theater category campaigns.  


[Theaters_Outcome_vs_Launch]
<img width="243" alt="Theaters_Outcomes_vs_Launch" src="https://user-images.githubusercontent.com/45208773/131185891-504f6340-7233-45e0-944c-16960577b0df.png">

2. Using the formula we learned to find percentages in lesson 1.2.5, I was able to find that 61% of the campaigns over all the months and years were successful, 36% of the campaigns failed and 3% of them were canceled. 

**What can you conclude about the Outcomes based on Goals?**

There were zero play campaign projects that were canceled. Most of the successful play campaigns fell in between the goal amount of less than $1000 up to $10,000. The campaigns that had the goal of less than $1000 had the highest percentage of successful projects. This could be good for Louise since she wants to raise approximately $10,000 for her play. She can look at the play campaigns that met their goals in the amounts of $1,000 to $10,000 and use this information for her own campaign. 

**What are some limitations of this dataset?**

One of the limitations of this particular set we are looking at, is that we are only looking at the success/fail/cancel campaigns of the plays specifically. In the pivot table we created, we could have filtered out any of the categories of the other campaigns to see how the outcomes of those were different. They could have had a better or worse outcome than the theater campaign. 
There is a lot of data in this data set between the different categories of campaigns, countries the campaigns were in, and a wide range of goal amounts for each campaign. For Louise, I would assume that she would only want to hold her campaign to raise money for her play in one country. Whatever that country may be, let’s say the US for example, she would only want to look at the campaigns that took place in the US and its outcomes. Since Louise only wants to raise about $10,000 for her play, she could look at all the campaigns that hit their goals that fell between less than $1000 and about $15,000. Basically, she could throw out the information in the data set that doesn’t really pertain to her and her needs. 

[Outcomes_vsLaunch] <img width="241" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/45208773/131186417-b524e791-7a7e-4262-99fb-a8881397242a.png">

**What are some other possible tables and/or graphs that we could create?**

We could have used a bar graph to present the data. We would have the months on the x-axis and the number of campaigns on the y-axis. The bars would represent “successful”, “failed” or “canceled” campaigns. The bars for each outcome would be next to each other above the respective month. This graph is useful when displaying the outcomes of each month, but the line graph shows a better representation of how the campaigns fluctuated outcomes over the months. It makes it a bit easier to read. Below is an imagine of the bar graph we could have used. 

<img width="240" alt="Optional_BarGraph" src="https://user-images.githubusercontent.com/45208773/131186301-6f005e09-8e4a-431c-af1e-1f1599de6ef1.png">



