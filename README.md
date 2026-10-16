# NBA Player Analytics: Predicting Wins, Injuries, and Social Media Engagement

For our project we wanted to find which variables are most predictive of NBA player's wins, injuries, and social media engagement. It is important to know that we were not trying to prove causation, just predictability. We tried to find the most predictive variables by looking at correlation. We used three datasets to make regression plots and correlation matrices.

We found that for player wins, high efficiency, impact and minutes per game are indicative of high career wins. For injuries we were not able to find a significant predictor, only that players with less minutes per game are usually those who had injuries but this only reflects the idea that injured players do not play when recovering. Players with higher scoring output and impact usually have higher social media engagement.

## Datasets

- NBA Stats: https://www.kaggle.com/datasets/sumitrodatta/nba-aba-baa-stats
- Injuries: https://www.kaggle.com/datasets/loganlauton/nba-injury-stats-1951-2023
- Social Power: https://www.kaggle.com/datasets/noahgift/social-power-nba

Raw datasets can be found at data/00-raw

## Guide

- 03-FinalProject: contains the essential, it is the formal presentation of our project.
- 02-EDACheckpoint: contains the everything in 00-ProjectProposal & 01-DataCheckpoint plus the extensive exploratory data analysis we did to achieve our results.

## Limitations

- Social Media engagement dataset only contained 1 season with 239 players. To better and more accurate results we would need to find a dataset which contains far more seasons with even more players.
- Our project only shows correlation, so we are not finding any causes to player's wins, injuries or social media engagement, we are simply finding which variables can be used to predict either of those three out of an existing correlation between the two.

#
Social media engagement analysis (cleaning, correlation screening, position and team comparisons): Gareth Arroyo.
