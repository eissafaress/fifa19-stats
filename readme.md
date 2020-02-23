# FIFA 19
## by Faress Eissa


## Dataset

> The dataset chosen is https://www.kaggle.com/karangadiya/fifa19 which is detailed attributes for every player registered in the latest edition of FIFA 19 database.
> The dataset includes 18207 entries where each entry corresponds to a player.
> The original dataset includes 89 columns, but my investigation was done using a copy of the dataset which includes 31 columns including combined columns from the original dataset.



## Summary of Findings

> Players distribution among Nationalities shows that Englad is the Nationality with most players.
> Players distribution among Clubs shows that players with no club are the most abundant.
> Players distribution among Positions shows that Midfield players are the most abundant.
> log of Value column is normally distributed while log of Wage column is right skewed.
> Overall, Potential and Age distributions are all normal.
> Top clubs are plotted against summary statistics of Overall, Potential, Age and Wage. Observations are
- clubs' Potential development varies greatly which results in different order of strongest teams.
- Clubs with younger squads tend to have more Potential development.
- Clubs having higher Wage range doesn't necessarily means they have stronger squads.
> the relationship between Potential VS Age is Positive while Overall VS age is Negative.
> Although England has the most number of players, they are poorly Valued as each European and Latin American country has better players' Value scores than its Players.
> two of the most important attributes for a player in any position is Power and Mobility.
> Overall VS Wage have a positive exponential relationship
> Brazil has the best Overall scores on average.


## Key Insights for Presentation

> I chose pathways to focus on at the end of this project which are:
- The relationship between Nationality and Overall, having Position as a third variable as well, as it indicates which country generates players with best quality in each position on the field. It turns out Brazil is the best country to produce players at every position, followed by Spain and Argentina.
-  The relationship between Wage and Position having Overall as a third variable, and it shows that Midfield and Forward players tend to get paid more than other positions having the same Overall rating.
- The relationship between Position and various players' attributes, which shows that Mobility and Power are key qualities a player in any Position needs to be good at.
- The relationship between top Clubs and Overall, Potential, Age and Wage, and it indicates how different teams are expected to develop with younger teams having the most Potential development, moreover the highest paying Clubs are not necessarily the best Clubs in terms of Overall score.


## List of resources

> Kaggle dataset and kernels for guidance:
- https://www.kaggle.com/karangadiya/fifa19
- https://www.kaggle.com/dczerniawko/fifa19-analysis

> Udacity's Data Analyst Nanodegree exercises for sample tools and techniques

> Stackoverflow  
