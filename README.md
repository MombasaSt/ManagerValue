# ManagerValue

Below is a glossary that explains MgrValue.xlsx, each item at a time. Each statistic is for the season (year) the individual managed the team. All seasons where a club had a manager fired midseason are excluded.

All data from **Manager** to **TeamWAR** is from Baseball Reference; all data after that is from FanGraphs. See the bottom of the ReadMe for further glossary reading.

**Year** - The year the individual managed that team

**Manager** - The individual. IDs would likely be present for each individual in a larger dataset, but there are no duplicate names here.

**Team** - The team the individual managed

**Wins, Losses, and Ties** - The team's record of won, lost, or tied games

**DivisionFinish** - What place in the team's division that team finished

**PostseasonWins**, **PostseasonLosses** - Wins and losses in the postseason

**WorldSeriesWinner** - Y if the team won the World Series that season

**ChallengesAttempted** - The number of times the manager challenged a call made by an umpire on the field. _Challenges did not exist before 2014._

**ChallengesOverturned** - The number of times a manager's challenge plea was correct

**Ejections** - The number of times the manager was ejected from the game, usually for arguing with an umpire

**StolenBaseChances2nd** - The number of plate appearances where 2nd base was not occupied by a runner and 1st base was

**StolenBaseAttempts2nd** - Times a runner attempted to steal 2nd base, regardless of success

**StolenBaseSuccesses2nd** - Times a runner successfully stole 2nd base

**StolenBaseChances3rd** - The number of plate appearances where 3rd base was not occupied by a runner and 2nd base was

**StolenBaseAttempts3rd** - Times a runner attempted to steal 3rd base, regardless of success

**StolenBaseSuccesses3rd** - Times a runner successfully stole 3rd base

**SacBuntChances** - Opportunities for a sacrifice bunt, or where a bunt by the current hitter could move a runner to an unoccupied base. This includes a runner on first but not second OR a runner on second but not third.

**SacBuntAttempts** - Times a batter attempted a sacrifice bunt, regardless of success

**SacBuntSuccesses** - Times a batter performed a successful sacrifice bunt (the runner was moved to the correct place)

**PlateAppearances** - Defensive plate appearances managed, or the amount of batters the manager faced

**IntentionalWalks** - The amount of batters a manager faced and intentionally walked

**PinchHittersPerGame** - The amount of pinch [substitution] hitters used by a manager in a game on average

**PinchRunnersPerGame** - The amount of pinch [substitution] runners used by a manager in a game on average

**PitchersPerGame** - The amount of pitchers used by a manager in a game on average

**TeamWAR** - The team's total Wins Above Replacement on the season. All player's WAR - or what is effectively their value compared to the average bench player - added together makes the team's. Note that Baseball Reference and FanGraphs calculate WAR differently; the dataset uses Baseball Reference's methods.

**AvgPHLeverageIndex** - The average leverage index of the situation when a pinch hitter was substituted in. Leverage index is a measure of how much a game is "on the line" at a given moment, where 0.85 is low leverage and 2.0+ is high leverage.

**BattingClutch** - How "clutch" a team is hitting-wise, or how much better (or worse) they are in high leverage hitting situations than a context-neutral environment. This is calculated by taking each player, dividing their win probability added (WPA) by their individual leverage index, subtracting the league-wide equivalent, and adding all of these up.

**ShutdownsPerGame** - A shutdown is when a reliever accumulates at least 0.06 Win Probability Added (WPA) over a single game. WPA is a measure of the expectancy of a team to win in the given situation.

**MeltdownsPerGame** - A meltdown is when a reliever's Win Probability Added (WPA) amounts to -0.06 or less over a single game. WPA is a measure of the expectancy of a team to win in the given situation.

**PitchingClutch** - How "clutch" a team is pitching-wise, or how much better (or worse) they are in high leverage pitching situations than a context-neutral environment. This is calculated by taking each player, dividing their win probability added (WPA) by their individual leverage index, subtracting the league-wide equivalent, and adding all of these up.

Wins Above Replacement (WAR): https://www.mlb.com/glossary/advanced-stats/wins-above-replacement
Leverage Index (LI): https://library.fangraphs.com/misc/li/
Win Probability Added (WPA): https://library.fangraphs.com/misc/wpa/
