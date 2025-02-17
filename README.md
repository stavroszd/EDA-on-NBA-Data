# NBA Team and City Population Correlation Analysis
This is my approach to the assignment in the 'Applied Data Science using Python' of the UoM. 
Essentially, this project performs an analysis of the correlation between NBA team win percentages and their respective cities' population. 
The analysis uses data from the NBA's 2018 season and city population data to explore if there is a relationship between a city's size and its NBA team's performance.
In order to explore this we calculate the pearson coefficient - through these procedures. 

- Handling missing data and keeping what we need
- Cleaning team names to ensure proper matching - this is done by a function that I have developed to work on NHL,NFL and MLS data as well (automation) 
- Standardizing city names - using a pretty cool algorithm of seeing if the team name starts with a city's name. 
- Merging the cleaned city population data with NBA teams' win percentages and then calculating the Pearson correlation. 
