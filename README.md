# kickstarter-analysis
Performing analysis on kickstarter data to uncover trends. 
# Louise’s Kickstarter Analysis (by Maha Shah) 

## Overview of the Project 

This project provides an analysis for a Kickstarter campaign for Louise. She requires an analysis performed to determine how the various campaigns met the fundraising goals following the end of her play Fever. Their performance is evaluated in relation to the launch dates and the fundraising goals. The first part of this report provides a summary of fundraising success of campaigns by launch months. The second part provides an overview of the campaigns based on the success of the fundraising goal. Finally, this report concludes with further analysis and recommendations for the data provided. 

## Analysis and Challenges 

### Analysis of Outcomes Based on Launch Dates 

![Theater_Outcomes_by_Launch_Date](https://github.com/msha789/kickstarter-analysis/blob/a352fdfcc5836b5438540bcab1c37b32c1acd0b2/Parent%20Category%20Outcomes.png)

Following the addition of a year column to the main worksheet, I proceeded to make a pivot table for the dataset. This pivot table was filtered for ‘parent category’ and ‘years’, with the columns being ‘outcomes’ and rows and values being the dates and their count respectively. 

Once created, I sorted the ‘parent category’ to theater and the column labels to be in descending order. This filtering was used to plot a line graph. 

This analysis is performed on outcomes based on the launch date for the fundraiser shows that particularly for theater campaigns, overall, there were almost twice as many successes as compared to failed campaigns. A total of 37 campaigns were canceled, representing 2.7% of all campaigns launched from 2009 to 2017. The months of May and June were the most successful, respectively. The least successful was the month December. 

### Analysis of Outcomes Based on Goals

![Outcomes_vs_Goals](https://github.com/msha789/kickstarter-analysis/blob/a352fdfcc5836b5438540bcab1c37b32c1acd0b2/Outcomes%20vs%20Goals.png)

A new sheet was created in the workbook. Goal amounts from the original dataset were categorized in 12 categories with intervals of $5,000 each. Within each of these categories a countifs function was used to populate the number of successful, failed and canceled plays. The sum function was used to produce the totals for each goal amount category. 

Taking a further look at the outcomes of the campaigns based on the goals, it can be seen that campaigns that were most successful were in category of goals less than $1,000. For goals higher than $20,000, there was a greater percentage of failed campaigns. Campaigns ranging from $35,000 to $45,000 has a higher percentage of successful campaigns as opposed to failed, however, goals higher than this amount had a significantly higher failure rate. 

### Challenges and Difficulties Encountered

A challenge encountered was to figure out the proper syntax for the countifs function. The proper placement of the quotation marks to properly guide the formula to look for a specific value with a selected field was something I had to learn by breaking down the formula with the help of google and excel. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The above analysis for theater campaigns shows that fundraising campaigns are more successful in the summer months of May and June. End of the year campaigns are less likely to be successful. 

- What can you conclude about the Outcomes based on Goals?

About half of all projects had a fundraising goal of $1,000 to $4,999. Lower goal amounts for fundraising are more successful, as opposed to higher fundraising goal amounts. 

- What are some limitations of this dataset?

Most of the data collected is concentrated in the years 2014 to 2017. The earlier years did not have a lot of data points within it. Furthermore, this dataset also does not fully present the 

- What are some other possible tables and/or graphs that we could create?

A possible table could be created to compare the fundraising successes between in person theater, plays etc. and film and video or technology type of fundraising campaigns. This would entail a similar success, failure and cancelation count and categories with a pivot table as done earlier but with these distinct filters for the aforementioned categories. These differences can further be represented using a line graph. 
