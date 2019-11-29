# UVA_2019_SemesterProject_Learning FIFA players’ traits - What makes an elite soccer player?

![alt text](https://github.com/gladieschanggoodluck/UVA_2019_SemesterProject_Learning/blob/Photos/1122PHOTO.png)
In 2019, the FIFA roster includes a great number of players from a total of 136 countries. The top three participating countries based on the numbers of players are England, Germany and Spain. Using an interactive world map, it is possible to hover the cursor over any participating country of interest to ascertain its average “Overall Rating”. (https://10ay.online.tableau.com/#/site/gladiesuva/views/FIFA1125/Wordlmap_country?:iid=5)
![alt text](https://github.com/gladieschanggoodluck/UVA_2019_SemesterProject_Learning/blob/Photos/fig15.PNG)
A variety of player attributes are used to understand the individual skills needed to be an elite level player. Since the game of soccer involves many different field positions, each of which favor players with certain innate attributes/features as well as mastery of certain skills, the combination of position, features and skills were identified and analyzed. **First** is the correlations between players attributes and skills, **second** is the features needed to be an elite player in each position group or position. **Third** is each country’s strategic field formation used by the national team.
This study focuses on FIFA players, their nationalities and the traits they possess. The data was statistically analyzed by making correlations between players performance and their physical features and skills. The data was presented in both tabular and graphical formats. The summary of the results of players features is offered.
![alt text](https://github.com/gladieschanggoodluck/UVA_2019_SemesterProject_Learning/blob/Photos/fig1.png)
# Exploratory Data Analysis: 
The top FIFA soccer player based on overall performance is the Argentinian Lionel Messi. According to the data provided for the analysis, Messi’s most prominent qualities are: physicality, pace, passing and shooting ability.
![alt text]( https://github.com/gladieschanggoodluck/UVA_2019_SemesterProject_Learning/blob/Photos/fig2.png)
The overall top tcountry ranking based on the analysis were shown to be Brazil. 
![alt text]( https://github.com/gladieschanggoodluck/UVA_2019_SemesterProject_Learning/blob/Photos/fig3.png)
What is required for a country to achieve a high status or success in international soccer? Upon analyzing the correlation between overall player ratings and attributes, the strongest three are passing, dribbling and base stats. Because the purpose of this study is to try and understand overall player ratings based on nationality, the attributes of actual field position and a broader position groups must be included in order to establish what makes the best players based on their field position.
Using tuple to get the top index
![alt text](https://github.com/gladieschanggoodluck/UVA_2019_SemesterProject_Learning/blob/Photos/fig4.PNG)
# Postion
* Position CAM: Base Stats, Pace, Dribbling
* Position CB: Physicality, Defending, Base Stats
* Position CDM: Base Stats, Physicality, Defending
* Position CF: Base Stats, Pace, Dribbling
* Position CM: Base Stats, Dribbling, Pace
* Position GK: Base Stats, Dribbling, Pace
* Position LB: Base Stats, Pace, Physicality
* Position LF: Base Stats, Dribbling, Pace
* Position LM: Pace, Base Stats, Dribbling
* Position LW: Pace, Base Stats, Dribbling
* Position LWB: Pace, Base Stats, Physicality
* Position RB: Base Stats, Pace, Physicality
* Position RF: Pace, Dribbling, Base Stats
* Position RM: Pace, Base Stats, Dribbling
* Position RW: Pace, Base Stats, Dribbling
* Position RWB: Pace, Base Stats, Physicality
* Position ST: Base Stats, Pace, Physicality
![alt text](https://github.com/gladieschanggoodluck/UVA_2019_SemesterProject_Learning/blob/Photos/fig5.PNG)
# Position Group: Attacker, Defender, Goal Keeper and Midfielder
* Position Attacker: Pace, Dribbling, Shooting, Physicality
* Position Defender: Physicality, Defending, Pace, Dribbling
* Position Goal Keeper: Dribbling, Pace, Physicality, Shooting
* Position Midfielder: Pace, Dribbling, Physicality, Passing

Interactive scatter plots are made to allow the selection of attributes of interest to check the correlation, the color and size are also the variables which allow users to select. 
![alt text](https://github.com/gladieschanggoodluck/UVA_2019_SemesterProject_Learning/blob/Photos/fig6.PNG)
Since there are a total of 136 countries in FIFA in 2019, a further understanding of each field position group; player strength based on the continent, the top three performing continents in the positions of Attacker. Midfielder, Goal Keeper and Defenders are South America, Europe and Africa
![alt text](https://github.com/gladieschanggoodluck/UVA_2019_SemesterProject_Learning/blob/Photos/fig7.png)
![alt text](https://github.com/gladieschanggoodluck/UVA_2019_SemesterProject_Learning/blob/Photos/fig8.png)
The strategies and formations used by the respective top national teams are analyzed. In addition, pertinent team formations were analyzed in order to understand the correlation between formation and success and to score these formations on a national basis. 
It seems the national teams favoring more traditional formations, like 3-4-3 or 4-4-2, achieve success because of the balance between the safer defensive and the riskier offensive play-styles. An ideal defense will never lose a match. However, to win competitions teams need to win matches and that involves taking risks and scoring goals. 
Squad = ['3-4-3', '4-4-2', '4-3-1-2', '4-3-3', '4-2-3-1']
![alt text](https://github.com/gladieschanggoodluck/UVA_2019_SemesterProject_Learning/blob/Photos/fig9.PNG)
# Squad Overall
Nationality (Country, Squad, Rating)
* Germany 3-4-3 85.36
* Germany 4-4-2 84.82
* Germany 4-3-1-2 85.64
* Germany 4-3-3 85.91
* Germany 4-2-3-1 85.73
![alt text](https://github.com/gladieschanggoodluck/UVA_2019_SemesterProject_Learning/blob/Photos/fig10.PNG)
# Squad Overall
Nationality (Country, Squad, Rating) 
* France 3-4-3 85.64
* France 4-4-2 85.36
* France 4-3-1-2 86.36
* France 4-3-3 85.64
* France 4-2-3-1 85.55
![alt text](https://github.com/gladieschanggoodluck/UVA_2019_SemesterProject_Learning/blob/Photos/fig11.PNG)
# Squad Overall
Nationality (Country, Squad, Rating)
* Spain 3-4-3 86.36
* Spain 4-4-2 86.18
* Spain 4-3-1-2 86.91
* Spain 4-3-3 86.82
* Spain 4-2-3-1 86.82
![alt text](https://github.com/gladieschanggoodluck/UVA_2019_SemesterProject_Learning/blob/Photos/fig12.PNG)
# Squad Overall
Nationality (Country, Squad, Rating)
* Brazil 3-4-3 85.82
* Brazil 4-4-2 84.64
* Brazil 4-3-1-2 85.09
* Brazil 4-3-3 85.91
* Brazil 4-2-3-1 85.73
![alt text](https://github.com/gladieschanggoodluck/UVA_2019_SemesterProject_Learning/blob/Photos/fig13.PNG)
# Squad  Overall
Nationality (Country, Squad, Rating)                 
* England        3-4-3    82.82
* England        4-4-2    83.00
* England      4-3-1-2    83.00
* England        4-3-3    83.27
* England      4-2-3-1    83.18
![alt text](https://github.com/gladieschanggoodluck/UVA_2019_SemesterProject_Learning/blob/Photos/fig14.PNG)
