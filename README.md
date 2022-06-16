# Kickstarting with Excel

## Overview of Project
An analysis on kickstarter campaigns data to uncover trends for Louise. 

### Purpose
The projects purpose is to analyze a large crowdfunding data set for essential information on fundraising campaigns for theater plays. To analyze the relevant trends in the data it was first important to organize and sort the data by using different filters  including dates, categories, subcategories, and more, to help Louise a hopeful playwright launch a successful kickstarter campaign. Two graphs were also created to help visualize the outcomes associated with launch dates and goals. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
A  line chart  was created from a pivot table to visualize the relationship between outcomes and launch month. With the pivot table fields having parent category and years as filters, outcome in columns, Date Created Conversion in rows , and outcome again in values. 
The graph shows canceled campaigns (green) seems to stay constant year-round apart from the month of October, which appears to correspond to the failed campaigns (yellow) that seemed to fluctuate close to 40 for most of the year, with some irregular characterizes between September and November. The successful campaigns (orange) had three upward spikes in February, May, and October each followed by a gradual decline. The graph indicates Louise might have a better chance of launching a successful theater campaign by launching in the month of May. Though other factors and data should be consulted before making a conclusion. 

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/107153827/174146636-e9fd4469-a1d1-4482-8491-ea543a90b532.png)

### Analysis of Outcomes Based on Goals
A line chart was generated with the percentage of successful, failed, or canceled campaigns on the y-axis and the goal amount range on the x-axis. The chart shows in grey that no play campaigns were canceled. The percentage of successful campaigns in blue, shows the highest in goals amounts with less than $1000 at 76%. The successful campaigns then decreases until $35000 range, where it raises to 67% and then declines after $40000 range. The percentage of failed campaigns in orange shows that goal amounts between $45000 and $49999 have zero percent chance to succussed. 

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/107153827/174146852-a2592377-6236-4dfc-bded-0c4e04063745.png)

### Challenges and Difficulties Encountered
The most challenging aspects of this assignment was creating the table to generate the chart Outcomes Based on Goals. The difficulties of the COUNTIFS() function in excel, was extremely frustrating due to its length and complexity. I overcame this by only using the formula bar and starting with the first criteria range 1, criteria 1 and then adding the other criteria one at a time. I also used a [Markdown](https://www.markdownguide.org/cheat-sheet/) cheat sheet to help understand some of the basic syntax for writing this report for GitHub readme.md.
## Results
The graph Theater Outcomes by Launch Date indicate that the month of May would be the ideal time to launch a theater campaign. The data also suggest December would be the least favorable month to launch a theater campaign. The most successful goal amount range is less than $1000, followed by goal amounts between $35000 to $44999 range. It should also be noted that the percentage of failed campaigns shows that goal amounts between $45000 and $49999 have zero percent chance to succussed. 
Louise may also benefit from further filtering of the data; an example might be narrowing down to the location of the theater production to one country. Louise would run into some limiting issues with the dataset, if she selected Great Britain as the country for her play this would leave many unknown factors that could heavily influence her play, because a theater production could be vastly different in Bristol vs London. Another useful graph for Louise could be to compare outcomes with the duration of the kickstarter campaigns, this could give Louise a time frame for her campaign.
