# Python-project
Sports analysis for Indian Premier League using Python
Includes the use of mentioned libraries 
1. pandas as pd
2. numpy as np
3. matplotlib.pyplot as plt
4. ipywidgets as widgets
5. seaborn as sns
6. from IPython.display import display
7. from sklearn.preprocessing import LabelEncoder

# Overview
This dataset is about the Indian Premier League (IPL) cricket tournament until the year 2017. It contains detailed information on each IPL match played until 2017, including the date and location of the match, the two teams that competed, the result, and the scores. It also includes data on individual player performance, such as the number of runs scored, wickets taken, and catches made. Additionally, the dataset includes information about the IPL teams, such as the team name, home ground, and owner. I have used this dataset for my project to analyze it based on various different factors. I have used two different datasets to study the patterns - a) A match dataset listing all the matches that took place from 2008 to 2017, and b) A player by match dataset listing one row of each of the players that played these matches.

# Data Cleaning and Preparation
Data cleaning for this analysis includes renaming the columns in both datasets, merging the two datasets, removing/manipulating null values, deleting a few columns that were not required for the analysis, and renaming some values in a few columns that were incorrectly named.

# Team Performance Analysis
With this analysis, I have tried to understand how the teams performed over the 10 years. For this, the entire data set was sliced into only the part that was required for the analysis. The number of matches they played and the number of matches won out of those. This type of analysis and visualization help us understand the success pattern of teams and can be used in fantasy gaming platforms to make deductions on which team will be winning against which teams. Here, the analysis is done based on the wins of a team based on runs, the wins of a team based on wickets, and the total win percentage of every team. 

# Toss Analysis
In a game like cricket, teams have been assumed to be winning matches based on what they choose when they win the toss. In this analysis, I have tried to figure out whether this assumption is a fact or not. 

# Venue Analysis
In this analysis, I have tried to understand whether the venue affects the winning of the teams or not, what the 10 most famous and 10 least famous venues and whether the winning team wins by runs or by wickets.

# Player Performance Analysis
Here, I have analyzed the best players of the matches and noticed that they have mostly been from the winning team. Additionally, the best captains under whose captaincy the teams have won matches, the win percentage of each captain who has played more than 5 matches as captains, the age distribution of players, and age distribution by player roles.

