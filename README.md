# Counter-Strke: Global Offensive 


# CSGO Matches Data Link: Webscrapped 
https://www.hltv.org/stats/matches?startDate=all

## Project Presentation:
https://www.canva.com/design/DAD9aESRGAs/WbP7Oa99LHZ8ILX3rde5lA/view?utm_content=DAD9aESRGAs&utm_campaign=designshare&utm_medium=link&utm_source=sharebutton

### Project Details:
This project consist of rating and ranking teams.
Predicting which team will win from match.


#### Goals  
- The goal of the project is to  prediction which team will win from a match. I will be using match history to collect wins and losses. I will also rate the team based on their win/loss. After obtaning the win/lose rating and ranking of teams, I can then predict game outcomes for matches. 

## Project Findings:
- Based on rank and win/lose the models have a hard time predicting the correct winners. Situations where lower ranked teams beating higher ranked teams were incorrectly predicted. 
- Rank and win/lose rating is not enough for the models to predict accurately. 

#### Problems:
- Some lower ranked teams would beat higher rank teams.
- Some teams are currently not active throughout the years.
- Team members may have switched to different teams. 
- COVID-19 has prevented a tournament environment for teams to play in.
- Having fans maybe help or harm some teams. (similar to home team advantages).

#### Solutions:
- Create or find more features.
- Collect data only for active teams.
- Account for player skills on maps and weapons. (TrueSkill rate players)
- Obtain team win/loss on maps.

#### Recommendations for further developments:
- Have an updated team rating based on player rating.
- Include in-game weapon skills of players.
- Apply average of total player skills as team rating.
- Account for players switching to different teams and updating team rating.
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
* Selenium
* Scikit learn
* Microsoft TrueSkill


## Needs of this project
- data exploration/descriptive statistics
- data processing/cleaning
- statistical modeling
- identifying team ratings and ranks
- obtaining team win/lose
- predicting which team will win
- collecting team win/lose counts
- sorting through team matach history
- events teams have played in


## Getting Started

1. Clone this repo (for help see this [tutorial](https://help.github.com/articles/cloning-a-repository/)).
2. Webscrapper: Anh_Team_Web_Scrapper.ipynb
3. Teams_webscrapped (2012-2020): CSGO_TEAMS.csv
4. Data Cleaning: CSGO_DataFrame_Cleaning.ipynb
5. Teams_rank: CSGO_TEAMS_RANKS.csv
6. Teams_matches (after data cleaning): CSGO_TEAMS_MATCHES.csv
7. Model/Predictions: CSGO_Win_Predictions.ipynb


#### Project Members:

|Github: [Anh Phan](https://github.com/anhbiphan)

|Linkedin: https://www.linkedin.com/in/anh-phan-40a8b166/
