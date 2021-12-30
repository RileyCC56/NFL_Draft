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

## Resources:
https://stathead.com/football/draft_finder.cgi

## Visualization Webpage: 

## Summary:
