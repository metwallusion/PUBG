# PUBG
Data Science Project

Pubg work.rar contains 2 files
1. The ipynb file 
2. The dataset

\
<font size = 6 color='black'><b><u><i><center>.Pubg Dataset #1 killPlace.</b></i></u></center></font>
\
<font size = 5 color='brown'><center>By: Ahmed Metwalli</center></font>

<font size = 6 color='black'><b><i><center>Content</b></i></center></font>
\
\
<font size = 4 ><b>1. Introduction\
    \
    2. Data Explore And Data Wrangling\
    \
    3. Choosing Area Of Interest\
    \
    4. Data Visualization\
    \
    5. Predictions

<font size = 6 color='black'><b><i><u>Introduction<b><i><u></font>\
    \
<font size =4 color='blue'><i>Pubg is a great multiplayer online game that has conquered the market since 2018 till now. It contains my features and analytics to explore from variety of players. In this report we would like to investigate how do a player finish in the first place in terms of kill [killPlace #1] performing wrangling visualization and predictions.

<b>About initial data train_v2.csv</b>: Shape 4446966 x 29\
The data set, available here ['https://www.kaggle.com/c/pubg-finish-placement-prediction/data?select=train_V2.csv'], consists of 29 statistics collected for 4446966 players. <b>The statistics are</b>:\
Id: player’s Id\
assists: number of enemy that this player damaged and were killed by teammates\
boosts: number of boost items used\
heals: number of healing items used\
revives: number of times this player revived teammates\
damageDealt: total damage dealt. Note: Self inflicted damage is subtracted\
DBNOs: number of enemy knocked\
killPlace: ranking in match for number of enemy killed\
killPoints: kills-based external ranking of player [“0” should be treated as a “None” for rankPoints equal to -1]\
killStreaks: max number of enemy killed in a short amount of time\
kills: number of enemy killed\
headshotKills: number of enemy killed with headshots\
roadKills: number of kills while in a vehicle\
teamKills: number of times this player killed a teammate\
longestKill: longest distance between this player and a player killed at time of death\
rideDistance: total distance traveled in vehicles measured in meters\
swimDistance: total distance traveled by swimming measured in meters\
vehicleDestroys: number of vehicles destroyed\
walkDistance: total distance traveled on foot measured in meters\
weaponsAcquired: number of weapons picked up\
winPoints: win-based external ranking for player [“0” should be treated as a “None” for rankPoints equal to -1]\
winPlacePerc: percentile winning placement, where 1 corresponds to 1st place. It is calculated off of maxPlace [TARGET]\
rankPoints: Elo-like ranking of player, inconsistent and is being deprecated in the API’s next version\
groupId: ID group within a match. In different matches the same group of players will have a different IDs\
matchDuration: duration of match in seconds\
matchId: ID to identify match\
matchType: game mode such as: “solo”, “duo”, “squad”, “solo-fpp”, “duo-fpp”, “squad-fpp”, and other custom modes\
numGroups: number of groups we have data for in the match\
maxPlace: worst placement we have data for in the match








About the wrangled data: (The area of interest we have chosen 8 features to use in order to answer the research question)

<b><i><u><font size=4>Writing color encoding along the report:</u></i></font>\
<font color='indigo'>Questions: Indigo\
<font color='red'>Notes Or Wranglings: Red\
<font color='blue'>Explanations And Comments: Blue
