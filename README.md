# English Premier League 2020/2021 Analysis
#### by
## Alex Mogengo

# About the Project
This project aims to analyze the major football metrics and statistics for players and teams that were involved in the English Premier League 2020/2021 season. The goal was to compare and evaluate performance against other teams and players based on the recorded statistics using goals, assists, cards, passess and minutes played.

# Project overview
The project sought to understand important football metrics like:
* Total goals scored
  * By teams
  * By players - top scorers
  * By position
* Total assists provided
  * By teams
  * By players - top scorers
  * By position
* Age distribution
  * By teams
  * By position
* Number of players distributed by position
* Number of players by country of origin
* Penalties awarded
    * Total by teams
    * Penalties scored
    * League penalty conversion rate
* Aggression levels by players & team
* Positional contribution
  * Goals and assists
  * Defensive actions
  * Aggression (red and yellow cards)



# Prerequisites
The following open source packages are used in this project:
* Pandas
* Numpy
* Matplotlib
* Seaborn

# Dataset
The dataset used for this analysis contains raw premier league statistics data from matchday. This includes information like like the player names, teams, country of origin, number of games played, goals scored, assists provided, passes, cards issued. The data was obtained from [fbref](https://fbref.com/) for analysis.

# Data Cleaning
After importing the libraries we prepared the data for analysis:
* Checked and removed null values
* Checked and removed duplicated rows
* Checked leading and trailing errors

# Conclusions
After exploration of the data, analysis was done on the important metrics of team and player perfromance. Among the conclusions arrived in the research include:
* Most players who played in the league during the season were from England, followed by France and Brazil.
* Youngest player(s) had 16 years (Shola Shoretire, Dane Scarlett, Carney Chukwuemeka, Antwoine Hackford) while the oldest player was 38 years old (Willy Caballero) 
* Penalty conversion rate average in the league was 81.6%
* The passing accuracy average across the League was 77.8%
* Crystal Palace had the oldest squad (28.3 years) average & Manchester United had the youngest squad (23.8 years) average.
* For age destruction, most players in the league lied with 26-30 years > 21-25  years > 16-20 years and then 36-40 years being the least.
* Players between the age 26 - 30 years scored most goals.
* Teams most likely to be relegated received the most yellow cards
You can access the code in this [link](https://github.com/AlexOchoki/AlexOchoki-EPL_2020_2021_Analysis/blob/main/English_Premier_League_2020_2021_Analysis%20(1).ipynb)
