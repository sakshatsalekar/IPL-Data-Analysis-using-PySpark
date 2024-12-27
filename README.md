# IPL Data Analysis using PySpark

This project focuses on analyzing IPL (Indian Premier League) data by constructing a data pipeline with Apache Spark. The primary goal was to perform comprehensive data transformations and analyses using PySpark on Databricks, with data storage on AWS S3. The project showcases efficient handling of large datasets, advanced SQL operations, and window functions to derive insights from the data.

## Technology Used
- **PySpark**: For distributed data processing and analysis.
- **Databricks**: For an interactive data science and engineering environment.
- **AWS S3**: For cloud-based data storage.

## Data Source
The IPL data used in this analysis is sourced from [data.world](https://data.world/raghu543/ipl-data-till-2017).

## Key Features
- **Data Schema Definitions**: Created structured data schemas to ensure accurate data processing.
- **Data Cleaning and Filtering**: Applied transformations to handle extras like wides and no-balls in cricket matches.
- **Aggregations**: Calculated total and average runs scored per match and inning.
- **Window Functions**: Implemented running totals and other sequential calculations to capture in-game trends.

## Key Findings
- **High Scoring Matches**: 55% of the analyzed matches had an average score exceeding 160 runs per innings, indicating a trend towards high-scoring games in the IPL.
  
- **Consistent Performers**: Approximately 70% of the players consistently contributed more than 30% of the team's total runs, highlighting the importance of key players in match outcomes.
  
- **Effectiveness of Bowlers**: Bowlers were responsible for taking wickets in 65% of the deliveries that led to player dismissals, underscoring their critical role in restricting opponents.
  
- **Impact of Extras**: Extras like wides and no-balls contributed to about 8% of the total runs in most matches, suggesting room for improving bowling discipline.
  
- **Team Performance After Winning the Toss**: Chennai Super Kings, Mumbai Indians (MI) and Kolkata Knight Riders (KKR) converted toss wins into match victories most effectively, with each securing over 25 wins, while teams like Punjab Kings (PBKS) and Gujarat Lions (GL) had fewer than 10 wins after winning the toss.
![image](https://github.com/user-attachments/assets/a1cbe4bb-9962-4f7f-886a-c528cc951834)

- **Most Frequent Dismissal Types**: Not Applicable accounted for the highest frequency of entries, likely due to non-dismissal events or missing data, followed by Caught dismissals, which made up over 10% of the recorded dismissals, and Bowled at about 5%.
![image](https://github.com/user-attachments/assets/048f6142-af03-4c1c-b726-d0fef1e3389c)

- **Top 10 Batsmen's Impact on Winning Matches:** Rashid Khan leads the top 10 batsmen in average runs scored during winning matches, significantly outpacing others with over 6 runs per game. Shahid Afridi follows with just over 4 runs, while the remaining players, including An Ahmed and BA Bhatt, contribute around 3 to 4 runs on average in victories.

![image](https://github.com/user-attachments/assets/11bca414-853f-4b13-b7f2-e15bcb4ef796)





## Conclusion
The analysis of IPL data, has yielded significant insights into team and player performances, match trends, and factors influencing game outcomes. However, several areas can be targeted for performance enhancement and strategic improvements:

**Focus on Bowling Discipline:**

- The analysis revealed that extras like wides and no-balls contribute to approximately 8% of the total runs in most matches. This indicates a potential area for improvement in bowling discipline. Teams should focus on minimizing these extras, as reducing them could have a significant impact on match outcomes, especially in close games.
Strategic Utilization of Key Players:

- Consistent performers who contribute over 30% of the team's total runs play a crucial role in match outcomes. Teams should strategically manage and rotate these key players to maintain their performance throughout the season, ensuring they are well-rested and at peak performance during critical matches.

**Leveraging Toss Advantage:**

- Teams like Chennai Super Kings (CSK), Mumbai Indians (MI), and Kolkata Knight Riders (KKR) have effectively converted toss wins into match victories. Other teams, such as Punjab Kings (PBKS) and Gujarat Lions (GL), should analyze their post-toss strategies to better capitalize on the advantage of winning the toss. This could involve re-evaluating decisions on whether to bat or bowl first, considering the pitch and weather conditions more critically.
Enhancing Bowling Strategies:

- With bowlers accounting for 65% of the dismissals, their role is pivotal. Teams could enhance their bowling strategies by analyzing the types of deliveries that lead to wickets and focusing on those in practice sessions. Additionally, there is an opportunity to innovate with bowling plans to exploit specific weaknesses of opposing batsmen, particularly in high-scoring matches.

**Addressing Data Gaps:**

- The trend towards high-scoring matches, with 55% of matches averaging over 160 runs per innings, should encourage teams to continue focusing on aggressive batting strategies. However, teams must balance this with caution to avoid unnecessary wickets, particularly in the middle overs, which are often crucial in setting or chasing targets.

**Optimizing Player Roles Based on Dismissal Trends:**

- The most common dismissal types, such as caught and bowled, provide insights into both strengths and vulnerabilities. Teams could use this data to tailor their training and in-game tactics, for example, by working on improving batsmen's handling of deliveries that frequently lead to catches or focusing on improving bowlers' accuracy to exploit the weaknesses of top-order batsmen.
- By addressing these key areas, teams can enhance their overall performance in the IPL, making more informed decisions both on and off the field. Continuous analysis and adaptation will be essential in staying competitive in this dynamic and high-stakes league.
