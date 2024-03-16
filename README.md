# <ins>Projects</ins>

## [<ins>Predicting StarCraft Player Rank Using Performance Data<ins>](https://github.com/raychan6/predicting-starcraft-rank)

**Question**: Can I predict the rank of a StarCraft player based on their performance?

- Performed EDA on dataset, which turned out to include much more low rank players
- Built a logistic regression model with 86% training accuracy and 84% testing accuracy and a random forest model with 96% training accuracy and 82% testing accuracy
- Preferred logistic regression model due to less overfitting and higher testing accuracy, but it predicts low rank players more accurately than high rank players
- Perhaps there is a smaller gap between low and high rank players than expected 

| ![](/assets/img/starcraft-logistic-regression.png) |
|:--:|
| *Confusion matrix of logistic regression model (0: low rank, 1: high rank)* |

<br>

## <ins>[Nikola Jokic Machine Learning Project](https://github.com/raychan6/nikola-jokic-machine-learning-project)</ins>

**Question**: Can I predict whether the Denver Nuggets will win a regular season game solely based on Nikola Jokic's performance?

- Cleaned, analyzed, and visualized stats data in R
- EDA slightly suggests that there are diminishing returns on plus/minus as usage percentage increases
- Built logistic regression, support vector machines, random forest, and boosted trees model
- Support vector machines model correctly predicted 90% of wins and 90% of losses solely based on Jokic's performance

| ![](/assets/img/jokic_confusion_matrix.png) |
|:--:|
| *Confusion matrix for SVM model* |

<br>

## <ins>[LeBron James: The New Michael Jordan?](https://github.com/raychan6/lebron-james-data-analysis)</ins>

**Question**: Can we find any interesting insights from analyzing LeBron James's stats (2003-2022)?

- Cleaned and visualized stats data in Python
- Historically, LeBron's plus/minus is highest against Charlotte and lowest against Denver
- Game Score stat drops after playing 43 minutes in home games for Cleveland and 37 minutes in home games for Los Angeles. For Miami, there seems to be no significant difference in Game Score across minutes played or location.
- Even at age 37, LeBron's TS% was 61.8%, which is higher than much of his younger years

| ![](/assets/img/game-score-by-minutes.png) |
|:--:|
| *Game Score across Minutes and Location* |

<br>

## <ins>[Prep Baseball Report 2019-2022 Recruiting Project](https://github.com/raychan6/pbr-recruiting)</ins>

**Question**: Which counties have produced the most top 100 California baseball recruits in the last 4 years?

- Scraped recruiting data from Prep Baseball Report using _rvest_ package and cleaned data in R
- Los Angeles, Orange, and San Diego Counties have produced the most top 100 recruits, most of them being RHP and OF
- Created choropleth map for ease of presentation

| ![](/assets/img/recruit_counties_2019_2022.png) |
|:--:|
| *Choropleth map of the counties with the most top recruits* |
