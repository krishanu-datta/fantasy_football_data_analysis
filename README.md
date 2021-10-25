# OREO Cookie Fantasy Football Analysis

## Overview
This project is an amalgamation of various data investigations into the inner machinations of the OREO Cookie Fantasy Football League, the greatest fantasy football league in history. While I was in high school, the investigations were primarily done in Google Sheets or Microsoft Excel as I learned to unlock the powers of the spreadsheet. As I got to college, I gained familiarity with Python, Pandas and BeautifulSoup and the quality and significance of my inquiries began to shoot up. So, enjoy this growing collection of artifacts that represent my obession with numbers and fantasy football.

## File by File Walkthrough
### `2020 Advanced Positional Data.ipynb`
The inspiration for this investigation was simple: I wanted to see teams' starting lineups looked over the course of a season broken down by position. In particular, I wanted an easy way to answer the question of how many wins a team had without starting a 15 point QB (a long time metric award of the AMAs). In constructing this file, I came up with that answer and many more. These include:
- The number of different players started at each position for each team
- The average of each position started for each team
- The mean of each position started for each team
- The number of bust weeks of each position started for each team
- The number of startable weeks of each position started for each team
- The number of boom weeks of each position started for each team
- The percentage of points from each position started for each team
- The average number of players started per week of each position started for each team
- The average number of points by each position started for each team
#### Most importantly, I was able to provide the user a player by player breakdown of each team's positions, so that an image of the team's contributions could be visualized.
### `OREO League Game History`
This investigation was the first time I applied web scraping to my league, but the breadth and depth of my findings were immense. 
Here is a shortlist of some of the answers I found:
- The longest winning/losing streaks
- The largest/smallest margins of victory
- The highest/lowest scoring games by one team
- Percentage of manager's games scoring more than 100 points (standard for good week)
- Graphs of manager's rank over time
- Number of games by each manager over 120
- The highest/lowest scoring games by both teams
- The number of games managed by each manager
- The number of single digit (clutch) victories by each manager
#### My most recent addition to this data is creating a playoff tracker variable that acts as a tag to designate which teams would go on to make the playoffs. Using this variable, I am able to look at snapshots in time and see how teams went to make or not make the playoffs due to (or in spite of) their records, ranks and points.
