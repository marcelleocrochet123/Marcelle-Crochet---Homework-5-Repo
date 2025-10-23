In this Explanatory Data Analysis assignment, I used data from https://fbref.com/en/. This is a database of football (American soccer) stats and history statistics, scores and history for 100+ men's and women's club and national team competitions.
In https://fbref.com/en/, I took data from three National Womens Football League clubs; Angel City FC, Washington Spirit, and North Carolina Courage. 
I compiled all of their player stats from their most recent 2025 season.
The variables of interest are the age of the players (Age), minutes played (M.Played), and goals scored (Goals). 
For the distribution of NWSL players bar graph, the statistics I ran were the median and IQR of the bar graph due to its slight skew right. For the scatter plot of Minutes Played and Goals scored, I calculated the Pearson Correlation Coefficient and conclude there is a small positve relationship between the minutes played and total goals scored per player.
The dataset is imbedded in R, and you do not have to download it to your computer seperately as it will draw straight from Github.
There were a modifications made to the dataset. I had to delete four unusable digits off of the NWSL players recorded ages. 
After this, there are no modifications made to the dataset.
You must install the packages listed, and check they are in your library. 
After, this the code should run smoothly.
