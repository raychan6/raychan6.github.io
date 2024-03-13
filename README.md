# <ins>Projects</ins>

## [Nikola Jokic Machine Learning Project](https://github.com/raychan6/nikola-jokic-machine-learning-project)

**Question**: Can I predict whether the Denver Nuggets will win a regular season game solely based on Nikola Jokic's performance?

- Cleaned, analyzed, and visualized stats data in R
- EDA slightly suggests that there are diminishing returns on plus/minus as usage percentage increases
- Built logistic regression, support vector machines, random forest, and boosted trees model
- Support vector machines model correctly predicted 90% of wins and 90% of losses solely based on Jokic's performance

| ![](/assets/img/confusion_matrix.png) |
|:--:|
| *Confusion matrix for SVM model* |

<br>

## [LeBron James: The New Michael Jordan?](https://github.com/raychan6/lebron-james-data-analysis)

**Question**: Can we find any interesting insights from analyzing LeBron James's stats (2003-2022)?

- Cleaned and visualized stats data in Python
- Historically, LeBron's plus/minus is highest against Charlotte and lowest against Denver
- Game Score stat drops after playing 43 minutes in home games for Cleveland and 37 minutes in home games for Los Angeles. For Miami, there seems to be no significant difference in Game Score across minutes played or location.
- Even at age 37, LeBron's TS% was 61.8%, which is higher than much of his younger years

| ![](/assets/img/game-score-by-minutes.png) |
|:--:|
| *Game Score across Minutes and Location* |

<br>

## [Prep Baseball Report 2019-2022 Recruiting Project](https://github.com/raychan6/pbr-recruiting) 

**Question**: Which counties have produced the most top 100 California baseball recruits in the last 4 years?

- Scraped recruiting data from Prep Baseball Report using _rvest_ package and cleaned data in R
- Los Angeles, Orange, and San Diego Counties have produced the most top 100 recruits, most of them being RHP and OF
- Created choropleth map for ease of presentation

| ![](/assets/img/recruit_counties_2019_2022.png) |
|:--:|
| *Choropleth map of the counties with the most top recruits* |
