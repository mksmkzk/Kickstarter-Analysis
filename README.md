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

Most of the challenges that were encountered during this analysis had to do with me being unfamiliar with the different functions that excel has to offer. One of them being the CountIfs(). In order to overcome these challenges, I had to search for the documentations of the function to determine how to set multiple conditions. Another challenge was learning how to use vlookup() and how the selection works. Overall, the assignment was clear. It took reading the documentation and then some trial and error to get all the results we needed.

## Results

- Two conclusions from the Outcome based on Launch Date that we got are that:
   1. Most of the outcomes were successful regardless of the month launched.
   2. The most successful time to launch a theater kickstarter is from April to August.

- From looking at the graph of the Outcome based on Goals, we can conclude that for the greatest chance of a successful play kickstarter, the goal should be below $10k.

- One limitation of this dataset is that the currencies are not all the same. This means that even though we made some of these charts, we did not convert the currency to USD and it may be skewing the results of the graphs.

- Another possible table that we can create would combine the first two graphs. Since we know that Louise launched a project that was below $10k, we can create a new table to count the outcomes of all plays that are below $10k and sort those by month launched. This will give us a better understanding of when is the best month to launch a project that is more related to what Louise is trying to do.

