# An Analysis of Kickstarter Campaigns
Some summary statistics on failed and successful kickstarter projects
# Kickstarting with Excel

## Overview of Project
Crowdfunding has become a very popular way for entrepreneurs, creatives, and individuals to raise capital from investment backers on the internet. These projects may include things in the medical device field, consumer goods, app development, and creative projects. Kickstarter is a popular crowdfunding site, and in this project, I utilize data from Kickstarter to analyze trends of crowdfunded projects in the theater industry across the world.
### Purpose
My aim is to better understand historical trends in campaign outcomes, looking at time-series data and the financial goal that each creator established. In this analysis, a play is “successful” if the pledged dollar amount exceeds the campaigns goal, and a play is “failed” if pledges do not meet the fundraiser’s goal. One important note is that I do not signify the degree of success or failure. A play that is 200% funded and a play that is 100% funded are both counted equally as a success. Projects may also be canceled. Future playwrights can utilize this data to give them insight into some common characteristics of successful or failed campaigns, so that they can tailor their funding goal and campaign creation timing that reflects what has previously been successful. Additionally, Kickstarter can utilize this analysis structure to give them insights across all of their campaigns in order to better understand their customer and backer’s behavior. They can leverage these insights to understand seasonality in their business, and take action on marketing campaigns to support their creators and drive traffic to their site.  
## Analysis and Challenges


### Analysis of Outcomes Based on Launch Date

For this analysis, I created a line graph that summarizes the outcomes of theater campaigns based on their launch date, evaluated at each month across all available years. The graph can be found here: ![Theater_Outcomes_vs_Launch](Macintosh HD/Users/owendougherty/Desktop/Analytics Bootcamp/Module 1/Resources/Theater_Outcomes_vs_Launch.PNG)

There is a casual positive correlation between successful and failed campaigns. On average, the summer months of May, June, July and August had the highest number of successful campaigns. Additionally, there are fewer successful campaigns launched in November and December.

### Analysis of Outcomes Based on Goals
Next, I analyzed campaign outcomes of plays, a subcategory of theater, based on the fundraisign goal that the creator set. The funding benchmarks that I used are in increments of $5000 up to $500000, and any projects over $50000 are counted all in the same group. There are 1046 total projects in the plays subcategory. Project outcome is shown as a percentage of successful and unsuccessful divided by the total number of projects in each goal range. The chart “Outcomes of Plays on Kickstarter Based on Goal” shows that campaigns with a goal of less than $5000 have the highest success rate of being funded. That chart can be found here: ![Outcomes_of_Plays_Based_on_Goal](Macintosh HD/Users/owendougherty/Desktop/Analytics Bootcamp/Module 1/Crowdfunding Analysis/Resources/Outcomes_of_Plays_Based_on_Goal.png) 

As the goal increases, the percentage of successful campaigns tends to decrease. Of these 1046, 888 of them have a funding goal of less than $10,000, approximately 85% of all plays. It is important to remember this as we look across the chart, as the sample size decreases drastically after that $10,000 threshold. 76% of all plays with a goal of less than $1000 are successful, and only 2 of 16 projects with a goal over $50,000 are successful – a fail rate of 87.5%. 

### Challenges and Difficulties Encountered
I did not face any direct challenges creating my analysis, but there are some areas that might require further exploration. One area that might present a problem in the data is that studying trends in the theater industry as a whole encompasses the subcategories of plays, musicals, and spaces. The production costs of a two hour musical may be entirely different than that of a 1 hour play, and may require more staff, equipment, and space constraints. This would affect a creator's fundraising goal to meet these varied costs. In future analyses of the theater industry, these are just a few of the variables that would need further exploration.

## Results

One conclusion that I can draw from the Outcomes Based on Launch Date graph is there is some degree of seasonality to theater Kickstarter campaigns, where more campaigns are launched in the summer months than the winter months. On average, May has the highest number of theater Kickstarters launched at 166 and December has the lowest total launched at 75. The number of canceled projects across each month is ambiguous and is a small percentage of all launched campaigns. In conclusion, I would advise that any young theater producer who is launching a campaign to aim for launching their project in May, as historically that has the highest number of successful campaigns. 

Based on the Outcomes Based on Goals chart, I conclude that, keeping sample size in mind, plays with a goal of less than $10000 historically have performed better than plays above $10000. There is a much more robust sample size for these plays, which strengthens this conclusion. The chart marks a sharp uptick in fail rate in the $45000-$49999 range, but that is based on only one data point. 

One limitation of this data set is that we are potentially missing some qualitative data on each play. It might be interesting establish some accounting for the creator's history, or how long the potential production is. For example, a producer who has already directed and written 4 plays might have a better liklihood of receiving funding compared to someone working on their first production. 

Since our analysis spans several years, it might be interesting to look at Kickstarter's growth rate across those years. If the site significantly increased in popularity from 2014-2017, it may be that campaign success and total campaigns could rise due to increased traffic and brand awareness. In the future, I'd want to create a graph that shows total project volume by year, to establish if site and campaign volume changed at all over the years. 
