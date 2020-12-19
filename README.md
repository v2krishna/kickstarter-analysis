# Kickstarter Campaign Analysis
 
 Performing Data Analysis on Kickstarter compaign data to uncover trends.
 
## Overview of Project
Kickstarter is one of the crowdfunding companies that helps to brings lot of creativity ideas/projects to life through the funds raised during the campaign.  Each campaign will have  a Launch Date and duration  and a goal amount. The goal amount should be met within duration of the campaign, otherwise no funds are collected. Around 400K projects has been on the Kickstarter campaign. Different kinds are projects are campaigned which fall unders one of the many categories like films, technology, food-related , etc.

We are focuing on analyzing the data which campaigns are successful and met the goals by Geogrpahic Regions for Theaters based on the outcomes ang goals.


### Purpose: 
Help Louise in taking better decisions when to start her kickstarter compaign for her "Fever" play. Do some exploratory analysis and provide the outcomes of the exploratory analysis.

## Analysis and Challenges
  Gather the Sample Data related to Kickstarter information. Peformed Data Cleansing Activities like sorting, filtering unwanted data, calculated/derived some of the
  columns like Category, Subcategory out the existing data points.Build interactive visualizations thats helps in visualizing the Outcomes by Category/Country, 
  perform the Trend Analysis on the Goals.

### Analysis of Outcomes Based on Launch Date
![OutcomesBasedOnLaunchDate](/resources/Theater_Outcomes_vs_Launch.png)

* Based on the Visualization Theater campaigns are more successful that are launched during May to July months when compared to the other months
* Jan, Feb , Mar and Aug are having around same percentage of success rates, Zero Campaigns are been cancelled once started.

### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](/resources/Outcomes_vs_Goals.png)

*	Plays subcategory which are in range of less than 4999 and goals between 35000 to 45000  are most successful.
* Any goals which are greater than 45000 has highest number of failures.
* Goals which are less than 7000 has higher success rate.

### Challenges and Difficulties Encountered
  Data has been provided is not readily useful to perform the analysis, Data has to be cleansed, formatted, sorte, then had to derive the variables thats are been not
  available points. Had to change the unix dateformats
    * Convert the UnixTimestamp in more readily format.
    * Had to derive the numerical data/Key Figures for performing the analysis. 
    
 ## Results

- Conclusions based on the Outcomes based on Launch Date?</b>
  As mentioned earlier, we can derive below: </b>
   * Theater campaigns are more successful that are launched during May to July months when compared to the other months.
   * Around the same number of compaigns are been failed during May to Aug.

- What can you conclude about the Outcomes based on Goals? </b>
   * Goals which are less than 10000 has higher success rate.
   * Any goals which are greater than 45000 has highest number of failures.

- What are some limitations of this dataset?
   * Very limited sample has been provided to perform the analysis, around 1% data has been used.
   * Backers Demographics is not available to arrive which campaign has received most funds from which region.
   * Scope of the analysis was limited to only some variables , not sure which other variables are affecting campaign's outcomes at this stage.
   * Cannot completely come to a solid conclusion based on the above data, need to perform some more Exploratory Data Analysis of the data.

- What are some other possible tables and/or graphs that we could create?
   * Duration of each campaign by Category / Subcategory vs Outcomes.
   * Pledged vs Goal Comparision
   * Backers Demographic vs Donations
  
