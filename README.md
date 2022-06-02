# Kickstarting with Excel
## Overview of Project
The purpose of this analysis is to determine possible factors that contribute to the success or failure of fundraising campaigns on the Kickstarter platform.  The data is from a collection of over 4,000 historical Kickstarter campaign records from 2009 to 2017.

Below is the link to the Excel file that contains all of the data used in the "Kickstarter" tab

[Kickstarter_Challenge_Excel_File](Kickstarter_Challenge.xlsx)

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
For this analysis, I use the pivot table to look at the fundraising outcomes for all theater projects in the dataset.  In particular, I want to see if the campaign launch month will have a correlation to the success or failure of the outcomes.  I created the below chart from the data to help visualize the data.

![Theater Outcomes by Launch Date](Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
For this analysis, I like to see if different fundraising goals may contribute to the success or failure of campaigns for all projects in the plays subcategory.  To do that, I separated data into different buckets by fundraising goal dollar amount and list out the corresponding outcomes by counts and percentages.  I created the below chart from the data to help visualize the data.

<img src="Outcomes_vs_Goals.png" alt="Outcomes_vs_Goals_chart" title="Outcomes_vs_Goals_chart" width="500px">
![Outcomes_vs_Goals_chart](Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

## Results
- Two conclusions I can draw from the Theater Outcomes by Launch Date are
    1. Fundraising campaigns for theater projects tend to have a higher success rate if launched during the months of May, June, and July. 
    1. Campaigns launched during December tend to have a lower success rate
- Conclusion from the Outcomes based on Goals is that most fundraising campaigns for Theater/Plays have a budget goal of less than $15,000.  For these lower budget plays, projects with a fundraising goal of less than $5,000 have a high rate of success (over 70% success rate).
- Some limitations of this dataset to note for the two analysis are:
    1. For the analysis of outcomes based on launch date, data are aggregated from a spend of nine years.  Although the aggregated data seems to indicate the Summer months have a better success rate, when looking at individual years, the pattern is not as clear.  Thus the aggregated data may have less predictive power than one may expect 
    1. sample size for higher budget Theater/Plays projects are limited, therefore the historic success rate for these higher budget campaigns are less useful in predicting future success rate for a similar type of projects
- Some additional analysis ideas for this set of data includes:
    1. It will be interesting to look at the ratio of success vs. failed campaigns by year and by size.  The data may show success rate can be impacted by economic conditions.
    1. We can also do some analysis on whether "staff pick" makes a difference in campaign outcomes
