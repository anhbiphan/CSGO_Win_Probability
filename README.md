# Counter-Strke: Global Offensive 


# CSGO Matches Data Link: Webscrapped 
https://www.hltv.org/stats/matches?startDate=all

## Project Presentation:


### Project Details:
This project consist of rating and ranking teams.
Predicting win probabilities for teams.
Predicting which team will win.


#### Goals  
- The goal of the project is to  prediction which team will win from a match. We will be using match history to collect wins and loses. We will also rate the team based on their win/lose. After obtaning the win/lose and ranking of teams, we can then predict game outcomes. 

## Project Findings:
- Based on rank and win/lose the models have a hard time predicting the correct winners. Situations where lower ranked teams beating higher ranked teams were incorrectly predicted. 
- Rank and win/lose is not enough for the models to predict accurately. 

#### Problems:
- Some teams are currently not active.
- Team members may have switched to different teams. 
- COVID-19 has prevented a tournament environment for teams to play in.
- Having fans maybe help or harm some teams. (similar to home team advantages).

#### Solutions:
- Collect only active teams.
- Account for player skills for maps and weapons.
- Obtain team win/lose on maps.

#### Recommendations for further developments:
- Have an updated team rating based on player rating.
- Include in-game weapon skills of players.
- Averaging player skills and applying to team rating.
- Account for players switching to diff. teams and updating team rating.
- Improve model.


### Methods Used
* Statistics
* Data Cleaning
* Data Organizing/Exploring
* Feature Engineering
* Machine Learning
* Data Visualization
* Predictive Modeling


### Metrics Used:
- roc_auc
- accuracy

## Models Used:
- GradientBoostedClassifier
- Ensemble (RandomForrestClassifier)
- LogisticRegression
- SVM

    
### Technologies
* Python
* Pandas, Jupyter
* Numpy
* Scikit learn
* TrueSkill


## Needs of this project
- data exploration/descriptive statistics
- data processing/cleaning
- statistical modeling
- identifying team ratings and ranks
- obtaining team win/lose
- predicting which team will win
- collecting team win/lose counts
- sorting through team matach history
- event teams have played in
- 

## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Raw Data is being kept https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if
3. Webscrapper: Anh_Team_Web_Scrapper.ipynb
4. Teams_webscrapped (2012-2020): CSGO_TEAMS.csv
5. Data Cleaning: CSGO_DataFrame_Cleaning.ipynb
6. Teams_rank: CSGO_TEAMS_RANKS.csv
7. Teams_matches (after data cleaning): CSGO_TEAMS_MATCHES.csv
8. 
9. 



#### Project Members:

|Name     |  Github   | 
|---------|-----------------|
|[Anh Phan](https://github.com/anhbiphan)

