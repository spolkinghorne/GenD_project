# Generation Data Project
---
## Executive Summary
The Generation Data project needed to focus on creating an actionable dashboard or workflow with regard to political campaigning. The people on canvassing teams are the force behind these campaigns. With the COVID-19 pandemic, canvassing and voting looks different this year. Thus, this project focused on finding analytical insight for the mailling ballot system. Ultimately, the was to use the data given to help drive tageting efforts to ensure the most number of voters returned their ballots. 

The main tool used for this project was Tableau. Several different SQL queries were used to create calculations that could aid in this analysis. 

**Insights to Note:**
- Most voters have returned their vote on the 10th or 15th day after it has been issued. Thus the voters that are within this time period should be targeted to return their ballot to encourage more returns.
- Congressional Districts 005, 006 and 013 have a high number of registered Democrat voters but the percentage of their mailed ballots returned after being issured is low. 
- There may be a trend in the lielihood of returning a mailed ballot depending on the day of week it was issued with the weekend being less likely to be returned but this insight requires further investigation to be concluded robustly.
- If a voter has not returned their mailed ballot after 35 days it is unlikely they will return the ballot.

## Data Source
Georgia Abseentee Records

## Pipeline Framework

> Load Data -> Clean Incorrect Data -> Transform and Add Columns -> Create Visualizations -> Analyze -> SQL Daily Script & Comparison

### Links

[Tableau Dashboard](https://public.tableau.com/profile/stephanie.polkinghorne#!/vizhome/GenerationDataProject/Dashboard1)