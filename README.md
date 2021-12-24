# kickstater-analysis

## Overview of Project

Louise’s campaing (Fever) came close to its fundraising goal in a short amount of time. Now, she wants understand the relation between to the launch dates and the funding goals using the Kickstarter dataset.

### Purpose

The purpose of this project is to analyze the Kickstarter dataset and provide Louise with a report where she will be able to understand the best time to launch a campaing and how the launch date relates to the fundraising goal.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

Using the Kickstater dataset filtered by the "Theater" parent category and considering the launch date as a dimension, we were able to determine the number of successful, failed, and canceled campaigns for each month launched. Analyzing the results, it is possible to see that the campaigns launched in May and June were more successful than in other months. However, failed and canceled campaigns followed a more linear behavior and did not give much output to the project results.

![Theater_Outcomes_vs_Launch](/resources/Theater_Outcomes_vs_Launch.png)


### Analysis of Outcomes Based on Goals

Using the Kickstater dataset filtered by Subcategory "Plays" and twelve fundraising goal ranges  we were able to determine the number of successful, failed, and canceled campaigns for each fundraising goal range. 

In total, we analyzed 1,047 Plays. The majority of Plays (694 plays that corresponde to 66% of the total) had a sucessful outcome. 
There were no canceled campaigns across any of the goal ranges.

Overall, Plays with goal of $4999 or less were the most successful ones. Plays with a goal range of less than $1,000 had the highest rate of success (76%) following by Plays with a goal range $1,000 to $4,999 that had a similar rate of success (73%).

On the other side, Plays with a goal range greater than $45,000 had the higest rate of failure, for example, the range between $45000 to $49999 had only one Plays and this one failed. Followed by Plays with a goal range greater than $50,000 (88%), where there were 16 Plays in total and 14 failed. 

![Outcomes_vs_Goals](/resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered

The conclusions of the analyzes are not completely accurate as there are some anomalies in the dataset.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

Firstly, we can say that the months of May and June are the best months to launch a campaign.
Also, December is the worst month to launch a campaign, as the number of failed and successful outcomes are almost the same. Which means the chance of failure is greatest in December.

- What can you conclude about the Outcomes based on Goals?

We can conclude that the smaller the Goal of your campaign, the greater your chance of success. Even though the result showed an anomaly in the range of $35,000 to $39999 and $40,000 to $44999, these two occurrences can be disregarded as the sample is very small compared to the total of Plays (9 Plays out of 1047).
It means that the the fundraising goal is inversely proportional to the success of your Plays.

- What are some limitations of this dataset?

There are some outliers in the dataset that could give the wrong result. 

- What are some other possible tables and/or graphs that we could create?

For example, in the first analysis, we could create a relationship between Launch Date and Goal Range to understand whether these failed campaigns had a high Fundraising Goal, or even to confirm whether the successful ones had a small Fundraising Goal associate. It would help to understand if the conclusion for Plays is correct.
