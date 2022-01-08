# An Analysis of Kickstarter Campaigns.

# Kickstarting with Excel

## Overview of Project

Louise recently started fundraising for a play "Fever" which ended up missing the goal by a little. She wanted to know how her fundraiser compared to others based on the launch date and their goals. We ended up performing analysis on the Kickstarter Data of Plays in the US to help Louise determine if and when to launch a crowdfunding campaign for her newest play.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![Theater Outcomes Based on Launch Date Chart](Resources/Theater_Outcomes_vs_Launch.png)

We performed this analysis by creating a pivot table to measure the outcomes based on the date launched. We put the outcomes in the column and the date launched in the rows section. We then removed the year from the rows and sorted the results by month. We added two filters to our pivot table, the year the kickstarter was created and the parent category. We set the parent category to "Theater". We then took our data and made the line graph above. As a final touch, we changed the color of the different outcomes to make the graph easier to understand.

### Analysis of Outcomes Based on Goals

![Outcome Based on Goals Chart Chart](Resources/Outcomes_vs_Goals.png)

We performed this analysis by defining the different ranges of goals to examine. From there, we used the CountIfs() function to get a count of all the successful, failed, and cancelled kickstarters that:

  1. Fell into the given goal range.
  
  2. Had the subcategory set to "Plays"
  
 Once we got the initial tally, we added them up to get the total outcomes number. Then we divided each category by the total tally to get the percentages of each category. Then we created the graph above by selecting the Goal range column along with the columns of the percentages of the different outcomes.

### Challenges and Difficulties Encountered



## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?

