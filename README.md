# Big-Ten-2021-Football-Rankings
This program automatically collects stats from players in each Big Ten football team from the following sites:
  1. https://www.sports-reference.com/cfb/schools/{team}/2021.html
  2. https://www.sports-reference.com/cfb/schools/{team}/2021-roster.html
  
  The first website contains each team's stats and the second contains each player's position.
  
Upon collecting each team's table of statistics based on the given categories: Passing, Rushing & Receiving, Defense & Fumbles, and Scoring,
it then simultaneously obtains the player's position using the second website to add the player's position and school of attendance to the
table. The dataframes or tables from each team are then combined into their corresponding categories and the players are ranked.

- Passing is ranked based on total number of passing yards.
- Rushing & Receiving is split into two different tables where the rankings are based on total number of receiving yards and total number of rushing yards.
- Defense is divided into three different tables where the rankings are based on total number of tackles, total number of sacks, and total number of passes defended.
- Scoring is ranked based on total number of points scored

The rankings are then written to an excel notebook which contains a total of 7 sheets:
  - Overall Passing
  - Overall Rushing
  - Overall Receiving
  - Defensive Tackles
  - Defensive Sacks
  - Passes Defended
  - Overall Scoring

 
