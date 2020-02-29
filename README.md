# Analysis of Kickstarter Campaigns in US

## Objectives
Louis is starting new campaign for plays in US.

Through the analysis of the historical data for Kickstarter campaigns in US, we are aiming to provide Louise with keys for successful campaigns

## Contents
1. Outcome Based on Goal Amount (Challenge Assignment Q1)
2. Distribution of Goal vs Pledged Amount 
3. Outcome Based on Launch Date (Challenge Assignment Q2)
4. Outcome Based on Campaign Length
5. Conclusion
6. Limitation

## 1. Outcome Based on Goal Amount
Changes of the success are high for campaigns with goal amount less than $5,000 or in between $35,000 and $40,000.
However, as shown in next section, any campaigns with goal amound higher than $20,000 are outlier.

![01 - Outcome based on goal.png](https://github.com/TaishiMatsuda/kickstarter-analysis/blob/master/01%20-%20Outcome%20based%20on%20goal.png)

## 2. Distribution of Goal & Pledged Amount
Setting the realistic goal is key to success.
 - Failed campaigns tend to have higher target than successful campaigns
 - Majority of successful campaigns collected $1,700 to $5,700.
 - Average percentage funded for successful campaigns are approx. 120%, which failed campaigns only collected 11% of the goal.

![02 - Goal vs Pledged.png](https://github.com/TaishiMatsuda/kickstarter-analysis/blob/master/02%20-%20Goal%20vs%20Pledged.png)


## 3. Outcome Based on Launch Date
May is good / December is bad...
![03 - Outcome by Launch Date.png](https://github.com/TaishiMatsuda/kickstarter-analysis/blob/master/03%20-%20Outcome%20by%20Launch%20Date.png)

In case of US, campaigns launched in summer have significantly higher chance of success than those launched in winter.

## 4. Outcome Based on Campaign Length
![04 - Outcome by Campaign Length.png](https://github.com/TaishiMatsuda/kickstarter-analysis/blob/master/04%20-%20Outcome%20by%20Campaign%20Length.png)

## 5. Conclusion
4 Important Aspects of Successful Campaigns for plays in US are
 - Set realistic target for Campaigns goal.
 - Launch the campaigns in Summer and avoid Winter (Oct-Dec).
 - Have plan to raise fund within 30 days.
 - Successful campaigns collects funds from more than 100 people
 
## 6. Limitation
- Louis asked for the relationship between campaign length and outcome but no data available for campaign length
 -- Calculated campaign length based on Date Created and Date Ended and created the box plot to see the relation (See 2.)
- Limited available data depending on the country or the category of interest
 -- Limited the analysis to US as there are prenty data available for US
- "Plays" is still a big bucket but no more details such as genre of plays are not available.
 -- For more in-depth analysis, we will require to dig into more details.
