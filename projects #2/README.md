# Studying Patterns Determining the Success of Computer Games

## Parameters determining the success of games in different regions of the world have been identified. Based on this, a report has been prepared for a computer game store to plan advertising campaigns.


1. [Core Skills and Tools](#core-skills-and-tools)
2. [Key-words](#key-words)
3. [Results](#results)
   

## Core Skills and Tools

- Python, 
- Pandas, 
- Matplotlib, 
- Data preprocessing, 
- Exploratory data analysis, 
- Descriptive statistics, 
= Hypothesis testing

## Key-words

Data preprocessing, histogram, boxplot, statistical test,
Student's t-test, pie chart


## Results

I analyzed the data for the period from 2013 to 2016. This period was chosen not by chance: looking at the graph of platforms with games released on them and total revenue, we noticed that by 2013, many platforms had stopped releasing games. Additionally, in 2013, two other platforms emerged that sold the highest number of copies. We also established an approximate "lifespan" of a platform - from the release of the first game to the release of the last one - up to 5 years.

Having the relevant timeframe, we identified the top five platforms that not only sold the most games throughout the period but also remained relatively stable in sales: 'PS4', '3DS', 'XOne', 'WiiU', 'PC'.

I found that critic scores are correlated with sales growth, both for the leading platform in terms of copies sold – PS4, and for the other platforms in the top 5. As for user scores, they hardly influence sales on PS4 and other platforms. We also discovered that the most common genres are not necessarily the best-selling ones.

There were created an approximate consumer profile based on the most popular sales categories in different regions:

*North America*:
- Platforms: X360 and XOne;
- Genres: Shooter, Misc, Sports;
- Rating: "M" ("Mature") — for adults (17+).

*Europe*:
- Platforms: PS4 and PS3;
- Genres: Racing and Sports;
- Rating: "M" ("Mature") — for adults (17+).

*Japan*:
- Platforms: PS4 and PS3;
- Genres: Role-Playing and Fighting;
- Rating: "T" ("Teen") — for teens (13+).

*However, when considering potentially profitable platforms and genres for all regions, the following can be highlighted*:
- Platforms: PS4/PS3 and 3DS;
- Genres: Action and Role-Playing.

Finally, several hypotheses was tested to understand how user ratings can vary. To do this, we took several platforms and genres with different levels of copies sold. As a result, we found that the average user scores for the PC and XOne platforms were equal. Regarding genres, the difference in average ratings between Action and Sports games turned out to be statistically significant.

Therefore, for the development of future marketing strategy, it's advisable for a potential client to pay attention to platforms with high critic ratings, the regional preferences, and also focus on genres popular among users, such as Role-Playing and Action.