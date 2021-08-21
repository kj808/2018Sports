# Sports
Description: Many individuals enjoy watching sport games. For some, it is more fun to predict the outcomes of teams. Based on cameron measurements, can game scores be predicted for certain team matchups?

Location: Data Science Graduate Course at KU

Dates: October 6, 2018

## Goal
* Predict game scores for team matchups

## Data
* [NBA ELO Dataset](https://www.kaggle.com/fivethirtyeight/fivethirtyeight-nba-elo-dataset). Very rich data set with date, season, matchup teams, scores of both teams and elo.

## Analysis
* I performed data rangling on the two data sets (i.e., normalized features, combined data sets, removing unrelevant entries, randomizing entries, transforming features for model via bag of words)
* I split lines into training, testing and validation based on the 80/10/10 rule
* I created two clustering models:Random forests and Logistic regression
* Visualized the clusters via matplotlib

## Results
All in all, determining the scores based on the teams and carmelo measurements does not output useful results. By viewing both random forests and linear regression, the variance score is extremely low compared to 1 and the error is quite high. However, based on the above graph, the means of the test set and predicted set is not highly different (about 10 points).

## Repository Contents

| Directory | Description |
| --- | ----------- |
| Data | Contains all of the datasets used in this project. |
| Libraries | If libraries are used, the exact distribution will be located here. Includes library, library name, and library version. |
| Models | Models generated for the project such as machine learning models. |
| Notebooks | Notebooks used for visualing the data. |
| Reports | The resulting reports on this project. |
| Src | Source scripts and other helper files located here. |

