# FIFA Dataset

## Project Overview:

This project delves into the fascinating world of international football by analyzing three distinct datasets: FIFA Men's National Team Rankings, FIFA World Cup History, and match-level data from recent tournaments. The analysis seeks to uncover insights into team performance, historical trends, and key moments in football history using various techniques like Exploratory Data Analysis (EDA) and statistical modeling.

## Datasets Details:

### FIFA Men's National Team Rankings:

This dataset provides current FIFA rankings for 211 national teams.
Key features include:
team: Name of the national team.
team_code: FIFA code for the team.
association: Regional football association (e.g., UEFA, CONMEBOL).
rank: Current FIFA ranking.
previous_rank: Previous FIFA ranking.
points: Current FIFA ranking points.
previous_points: Previous FIFA ranking points.


### FIFA World Cup History:

Details of FIFA World Cup tournaments from 1930 to 2022, including:
Year: Tournament year.
Host: Host country or countries.
Teams: Number of participating teams.
Champion: Winning team.
Runner-Up: Second-placed team.
Top Scorer: Leading goal-scorer(s) with goals scored.
Attendance: Total attendance.
Matches: Total number of matches played.
Match-Level Details from Recent Tournaments:


### Granular data from individual matches, such as:

home_team and away_team: Participating teams.
home_score and away_score: Final scores.
home_xg and away_xg: Expected goals for each team.
home_manager and away_manager: Managers leading the teams.
red_card, yellow_card: Discipline statistics.
substitute_in: Details on substitutions during the match.
Objectives:
Analyze the progression of FIFA rankings over time to uncover patterns and insights into team performance.
Explore historical trends from FIFA World Cup tournaments and identify top-performing teams and players.
Examine match-level data to identify key tactics and performance patterns in knockout vs. non-knockout stages.
Correlate ranking data with match performance to understand key success factors in international football.

## EDA

-Total Number of matches : 964

-Total goals scored: 2720

-Average goals scored per match: 2.8215767634854774

-Total attendance Over time: 44048413

-Average attendance Over time: 45693.3744813278

### 1. Times a Particular country is Winner, First runner up or  Second Runner up

#### WINNERS

![Number of times a Country won Fifa World Cup](https://github.com/user-attachments/assets/dab8997d-ea22-4a0a-8753-b6c883c33270)

#### FIRST RUNNER UP AND SECOND RUNNER UP

![First Runner Up', 'Second Runner Up](https://github.com/user-attachments/assets/837e4496-ed4e-4ddc-88e6-3f218db00947)

### CONCLUSION

Brazil won the most number of titles followed by Italy and Argentina.

Argentina , Netherland and West Germany won Most number of Runner up title.

Germany was Second runnner up for most of the times.


### 2. In which Year a Particular Team Participated.

![Team Participation Over Years](https://github.com/user-attachments/assets/b4b969fd-cf0c-4d46-b8d8-dd81d31b633e)


### OBSERVATIONS

Brazil is the only country to play all editions of the FIFA cup.

Countries are Qatar , Canada , Wales are new to the tournament.

Countires like Cuba, Israel , Kuwait , jamaica, Ukrain , Tongo etc. participated in only 1 edition of FIFA.



## ADVANCE EDA and CONCLUSIONS

### 1. PROBABILITY OF A TEAM WINNING KNOCKOUT MATCHES

![PROBABILITY OF A TEAM WINNING KNOCKOUT MATCHES](https://github.com/user-attachments/assets/2a5a3b91-07ab-4bd4-9b33-d37b456bc1b5)

### CONCLUSION

Italy: Teams facing Italy in knockout rounds can expect a challenging match. Italy has a 75% probability of winning in the quarter-finals, an 86% probability of advancing from the semi-finals, and a 67% probability of securing victory in the finals.

Spain - if it clears QF its wins title.

France - they have good record in QF comparatively not that good record in Semi and Finals.

Sweden never reaches a final.

if Argentina reaches semi final , it will surely win it.

### 2. CHECKING PLAYING STRATEGY OF TEAMS IN KNOCKOUT V/S NON-KNOCKOUT MATCHES

![Goals Scored by Teams Across Match Phases](https://github.com/user-attachments/assets/f9ced091-07df-423a-b438-e04a1a237dca)

### CONCLUSION
Generally teams play more agressive in 2nd half as compared to first half be it knockout or non- knockout tournaments.

In knockout Tournaments , Mexico only scored in First half, either they are defending in second half and maintaining the lead.

In knockout Tournaments countries Romaniya , Pero play with same agression in both the halves of the game.

Spain have very different strategy they place with almost equal agression in non knockout matches , however in knowckout matches they follow different plan , on first half they are into passive state (not scoring much) , however in second half they retaliate very voilently. Infact goals scored by them in first half and extra time are equal in number.

Canada never reached a knowckout stage , and even in non knockout stages they never scored a goal in second half. This can be their scope of improvement area , as they not scoring in the second half may be the reason they never made it to knockouts.

### 3. DOES SUBSTITUTION TURNS OUT TO BE FRUITFULL  OR NOT FOR THE TEAM.

![Goals Scored by Substituted Player](https://github.com/user-attachments/assets/f3afe7ce-66d2-4bcf-a754-a44495ad4ea5)

### CONCLUSION
No Team substituted player scored goal in FIFA.

Teams like France , Argentina , Portugal , Australia , Germany , Spain , Netherland have very high or positive impact of subsutituion on overall score of the team.

Positive impact of the substituion signifies that these teams have a strong management that act accourdingly , as these teams are also the top teams of FIFA, these effective substution may be one of the reason why these teams are most favourite teams of the world.

A team can rely on substituted player for overall improvement of score but not for the goals to be scored by substituted player.

### 4. TEAM EXPECTED PERFORMANCE AND ACTUAL PERFORMANCE

![Actual Goals vs  Expected Goals by Team](https://github.com/user-attachments/assets/b575c086-41d3-4679-8e54-3f4d81276f94)

### CONCLUSION
IN 2018 , Argentina Failed to take home advantages and underperformed in home games , However they over performed in non home grounds.

In 2018 Russia Was the most attacking team , as they scored 60% more goals then they were expected to score , this may be due to home condition advantage as in 2018 FIFA world cup was in Russia.

Russia was also the Underdog Team in 2018 , as it performed much more than expected.

Netherland was the underdog team of 2022, it scored 52% more goals than expected.

Among top teams Portugal scored 40% more than expected goals.

Most Overrated team of 2018 and 2022 was Brazil they scored 32% and 40% less goals than expected in 2018 and 2022 respectively.




