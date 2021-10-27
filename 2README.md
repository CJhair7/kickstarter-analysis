# Kickstarting with Excel

## Overview of Project

### The purpose of the analysis is to discover any existent correlations between the outcomes of the kickstarters and the dates in which they where launched and the goal amount that was set at the begining of each campaign.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
First I filtered the parent category to only show me the theatre kickstarters as that was Louis's focus. Then I sorted the theatre kickstarters by the month in which they where launched to be able to see if there where any correlations reguarding the month in which the project was launched and its outcome.
One should pay attention to the format used in the Date collums as this format can vary and needs to be in a correct format for filtering.
  The grafic ended up looking like this:
![Theater_Outcomes_vs_Launch png](https://user-images.githubusercontent.com/92558873/139000360-7afa1424-e6cd-4e6f-9090-bfdd7b428011.png)

### Analysis of Outcomes Based on Goals
First I needed to establish goal ranges that would help me identify the amount invested in each project. After, I began to sort the number of successful, failed, and canceled projects that fit in each of the ranges. Lastly, I converted the number of projects in each category to percentages so it could be represented in a better way. I did this with the formula (B/E)*100.
I found it a bit tedious to copy the same formula in cells B2:D13 so I found it easier to just copy the same formula in the first collum and just change the outcome type (to failed and cancelled), rather than changing the range manually.
This is what the grafic looks like:
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/92558873/139000331-3800a330-4686-479a-9a98-a2692ee3d1e9.png)



## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  1.) The months of May and June were the months with the highest success rates.
  2.) Decembre was the month woth the lowest amount of successful projects.

- What can you conclude about the Outcomes based on Goals?
 It's evident that projects with very high goal amounts (45000+), were very likely to fail. 
 Also, the exact opposite. Projects with low goals were very unlikely to fail.
- What are some limitations of this dataset?
 It can't tell us the exact elements Louis needs to ensure she creats a successful campaign.
- What are some other possible tables and/or graphs that we could create?
We could organize information so we can see if there is any relation between the lenght of the project and its outcome. (Using the time frame from date converted to date ended).
