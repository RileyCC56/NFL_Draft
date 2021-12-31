# NFL Draft Data and Summary
## Intro:
The following data was sourced from Stathead, an affiliate with Pro Football Reference source. In my attempt to web scrape the following data I was limited to only the first page of data or 100 columns worth of draft data. I do believe my experience was a limitation on receiving all 5,513 rows of draft data spanning from 2000-2021. 

The data I determined to collect was based on the decision of including one of the oldest current players of Tom Brady as he himself is outlier in regards to his success and draft position.

As I was limited to only 100 rows of data when web scraping, I manually clicked through each page and quickly copied and paste the data into an excel spreadsheet to gather all the information quickly.

The data itself was clean and organized and very easily prepared to be explored with a few changes. One transformation I determined was to categorize a few of the positions into one such as combing all data that fell under ‘NT’, ‘DE’, ‘DT’ as ‘DL’. I processed the same technique with the ‘OLB’, ‘ILB’, as ‘LB and ‘T’, ‘C’,’G’, as ‘OL’. By slightly adjusting the data to compress the position slightly I believed this will just make my end visualizations less intimating by having 10 positions rather than the original 19.  

In the timeframe from 2000-2020, there have been team location changes such as St. Louis Rams to the Los Angeles Rams, Oakland Raiders to Las Vegas Raiders, San Diego Chargers to the Los Angeles Chargers. With these slight changes I wanted to keep the original data for the original location just for my own personal curiosity and I understood that this would not have an affect of the final outcomes I was looking for. 

In research I found a similar analysis from a Dustin Ryan that I found visually interesting and applied a chart similar to his. With this knowledge I then created two new columns within the data frame that provided a True or False if the player within our data was ever rewarded with Pro-Bowl or First Team All-Pro accolades. 

## “The best ability is availability” 

The motivation I had behind this project was to generally get an understanding if a player’s position, and draft round played a possible relation to their success within the NFL. Understanding there are more variables that come into account to determine a player’s career success I was curious to see if an NFL team on draft day was torn between a decision that they would make a data driven decision. A decision that if they understand that a certain position has a higher probability of becoming a serviceable player to their team for years to come over another based on my recent findings.

## Tools:
Python, Pandas, MatPlotLib, Power Bi

![Presentation1](https://user-images.githubusercontent.com/81484054/147833267-16c8cf5e-55b6-4358-bf67-9c9b54e43b11.png)


## Resources:
https://stathead.com/football/draft_finder.cgi

## Visualization Webpage: 

https://app.powerbi.com/links/rCllXooYKz?ctid=ceae1e0f-43f7-4175-be6e-a37351af2598&pbi_source=linkShare

## Summary:
Slide 1
The following visualization shows the 20 years of draft results if a player was awarded with a Pro-Bowl, and First Team All-Pro accolade. 

Given the current data we do see that most of the players selected for a Pro-Bowl or First-Team All-Pro selection were selected within the first 100 picks of each draft. 

Slide 2
The average career length of a NFL player is 3.3 years, from the given graph we are able to see the average length for all 257 draft picks that were selected within the last 20 years. An obvious metric we find is that the early draft picks tend to have longer career lengths then those of the later picks.
One interesting aspect I found from this data is the history of the 80th overall pick. This particular pick has a below average career length of 2.64 years within the NFL. After further research I have found that within the past 20 years there have been zero awarded Pro-Bowl or First Team All-Pro players that were selected 80th overall. With this data maybe teams will be willing to trade away this particular pick given the recent track record.
The lower visualization’s shows the average career length per round. As the average career length is 3.3 years, we can see that players selected within the first four rounds are favored to have a career higher than the career average. 

Slide 3
Based on the following slide we can understand the average career length per position per draft round. As this data was the main motivation for the project, I am pleased to see we can find that based on our 20 years of data that certain positions have longer projected career lengths over others. For instance, a Tight End (‘TE’) is within the top 3 of career lengths for five of the seven rounds showing that a TE could be a safe pick towards the later rounds.

The objective of this visualization was to show that each round does provide the data that when selecting a certain position per round your chances of selecting a player with a longer career is compared to others.
