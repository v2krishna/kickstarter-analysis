# Kickstarter Campaign Analysis
 
 Performing Data Analysis on Kickstarter compaign data to uncover trends.
 
## Overview of Project
Kickstarter is one of the crowdfunding companies that helps to brings lot of creativity ideas/projects to life through the funds raised during the campaign.  Each campaign will have  a Launch Date and duration  and a goal amount. The goal amount should be met within duration of the campaign, otherwise no funds are collected. Around 400K projects has been on the Kickstarter campaign. Different kinds are projects are campaigned which fall unders one of the many categories like films, technology, food-related , etc.

We are focuing on analyzing the data which campaigns are successful and met the goals by Geogrpahic Regions for Theaters based on the outcomes ang goals.


### Purpose: 
Help Louise in taking better decisions when to start her kickstarter compaign for her "Fever" play. Do some exploratory analysis and provide the outcomes of the exploratory analysis.

## Analysis and Challenges
  Gather sample Data related to Kickstarter information. Peformed Data Cleansing Activities like sorting, filtering unwanted data, calculated/derived some of the
  columns like Category, Subcategory from the available information,.Build interactive visualizations thats helps in visualizing the Outcomes by Category/Country, 
  Perform the Trend Analysis on the Goals.

### Analysis of Outcomes Based on Launch Date
![OutcomesBasedOnLaunchDate](/resources/Theater_Outcomes_vs_Launch.png)
<br/>
Based on the Theater Outcomes on Launch Date Visualization, we can say that most of the Theater campaigns are successful that are launched during May to July months when compared to the other months. During Jan, Feb , Mar and Aug are having around same percentage of success rates, During Jan months more number of campaigns are been cancelled than the rest of the mongths which is very less.

### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](/resources/Outcomes_vs_Goals.png)
Based on the Outcomes vs Goals visualization, observed that plays subcategory which are in range of less than 5000 has higher chance of getting the campaigns successful, As the goal amount increases, the chance of getting the campaing successful get reduces, For some reason the Goal amounts which are in the range o 35k to 45K has same successful rate,
for this we mmight little more information ,why these higher amount goals got successful.

### Challenges and Difficulties Encountered
  Data has been provided is not readily useful to perform the analysis, Data has to be cleansed, formatted, sorte, then had to derive the variables thats are been not
  available points. Had to change the unix dateformats
    * Convert the UnixTimestamp in more readily format.
    * Had to derive the numerical data/Key Figures for performing the analysis. 
    
 ## Results

- <b>Conclusions based on the Outcomes based on Launch Date?</b> <br/>
  As mentioned earlier, we can derive below: </b>
   * Theater campaigns are more successful that are launched during May to July months when compared to the other months.
   * Same number of compaigns are been failed during May to Aug.
   * No campaigns are been cancelled during Oct , we need to check why there's are no cancellations.

- <b>What can you conclude about the Outcomes based on Goals? </b> <br/>
   * Goals which are less than 5000 has higher success rate, even the goals with range from 5000 to 10000 has higher chances of success rate, if we can avoid some pitfalls which
     caused the other campaigns fail. 
   * Any goals which are greater than 45000 has highest number of failures.
   
   Based on the above two main reasons we can recommend to have the plays campaign goal at this less than 5000 or 6000.
  
- <b>What are some limitations of this dataset? </b> <br/>
   * Very limited sample has been provided to perform the analysis, roughly around 1% data is been used to perform the analysis.
   * Backers Demographics is not available to arrive which campaign has received most funds from which region.
   * Scope of the analysis was limited to only some variables, not sure which other variables are affecting campaign's outcomes at this stage.
   * Cannot completely come to a solid conclusion based on the above data analysis, need to perform some more Exploratory Data Analysis of the data.

- <b>What are some other possible tables and/or graphs that we could create?<b> <br/>
   * Duration of each campaign by Category / Subcategory vs Outcomes., this will help us to understand how long each compaign was on and how many of the many successful with
     lesser duration.
   * Pledged vs Goal Comparision -- this visual, might helps us to identify each of the campaign how much has been pledged out which how many reached the goals.
   * Backers Demographic vs Donations-- helps to identify what kind of the backers are supporting the campaigns to narrow more on the backers who are supporting the theater
     plays will help to decide where to launch the campaign.
  
