# An Analysis of Kickstarter Campaigns

This report contains thousands of different KickStarter projects over various different fields in numerous countries.  Our friend Louise is very interested in theater and by using some of our findings she should hopefully have a better chance of success raising money than if she went into it blind.  Although some campaigns were more successful than others, Louise should take note of a couple data point we've discovered thanks to our charts and graphs.

# Analysis and Challenges

One analysis we did was a line chart to see if we could find out if a successful theater kickstarter campaign would be affecte by the month of the year it was launched. We used a pivot table to help filter out to just select the parent category theater and assigned our outcomes to the values in our excel spreadsheet [kickstarter analysis](https://github.com/DrewSears11/repo-kickstarter-analysis/blob/main/Kickstarter%20Analysis.zip) One challenge that got me on this analysis was finding the right categories to place in the filters, columns, rows, and values chart on the right.  I could not find how to get the months in for a while and was frustrated.  Finally I had a lightbulb moment and selected the date created which finally worked.  As you can see from the chart we can make a couple conclusions based on the start date.

![Theater Outcomes Based on Data](https://github.com/DrewSears11/repo-kickstarter-analysis/blob/main/Theater_Outcomes_Vs.Launch.png)

A second analysis we did was a line chart to see if we could find a correlation between outcomes based on the amount of money one hoped to raise.  We created a line chart using the percentage of each outcome from our excel spreadsheet [kickstarter analysis](https://github.com/DrewSears11/repo-kickstarter-analysis/blob/main/Kickstarter%20Analysis.zip) The biggest challenge for me for this one was using the COUNTSIF function in Excel to find the total number of successful, failed, and cancelled plays. It took a lot of time and detail to ensure I was drawing the right data from the main Kickstarter tab to get the data I wanted.  Once the first line of code was correct it was all downhill from there.  As you can see in the line graph below we can conclude a fairly obvious statement about this correlation.

![Outcomes Based on Goals](https://github.com/DrewSears11/repo-kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)


# Results
