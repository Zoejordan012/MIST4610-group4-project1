# MIST4610-group4-project1

## Team Name

## 71552 Group 4

## Team Members

## Ashleigh Myers @ashleigh-myers
## Daniel Ding @dd68158
## Shraeyas Muthaiah @shraeyasam
## Palak Kaur @palakxkaur 
## Zoe Jordan @Zoejordan012


# Problem Description
### Our NFL database was created as a representation of a database that would aid the leaders or administrators of the football league to make critical, impactful decisions about the league, and facilitate management. It is comprised of key categories of information including the stadium, game, team, players, head coach, and tickets. The NFL is one of the biggest players in a huge sports and entertainment industry, and there is a huge amount of data that needs to be organized, managed, and utilized. Sports leagues constantly change in response to unfair treatment of players, unfair exploitation of rules by players and teams, or changing tastes of consumers. With our database, the league managers and its committees can interpret information to make informed decisions for the integrity, sustainability, and profitability of the league, and handle the tasks they are responsible for, including creating or changing rules, approving ownership changes, training game officials, integrate technology, ensure competitive balance, and maintain legitimacy and entertainment of the game.

## Data Model
![Screenshot](Screenshot%202025-03-13%20at%201.02.12%20PM.png)

## Data Dictionary

![Screenshot](Screen%20Shot%202025-03-13%20at%209.55.01%20PM.png)










# QUERIES



## Query 1 Get Coaches of Teams with Above Average Wins
![Screenshot](Screen%20Shot%202025-03-13%20at%209.57.23%20PM.png)
### This query selects the coach's name, team name, and number of wins by joining the team and head coach table and selecting the coaches with wins above the average of other teams. This query is important to managers in the NFL for a variety of reasons. This can help evaluate the coaches' performance compared to their peers. This can be helpful when considering awards, brand deals/commercials, and hiring and recruitment. These high-performing coaches may be people that are more deserving of awards and certain brand deals. When other teams want to recruit coaches this may be a good way to find ones that are already preforming well at their current teams. 




## Query  2 Games with scores above teams average
![Screenshot](Screen%20Shot%202025-03-14%20at%206.35.57%20PM.png)



### It selects the game_id, date, score, and winning_team from the game table. It only includes games where the score is greater than the team's average score.This subquery shows the average score for all games played by that team. The outer query then compares each game's score to the average calculated by the subquery. If the game's score is above the average, it gets included in the result set. This query highlights games where a team performed better than usual, based on their scoring average. It helps in identifying high-performance games and understanding when a team exceeded expectations. Managers can use this information for analyzing games where the team scored above their average helps evaluate performance trends, highlighting peaks and consistency over time. By examining these high-scoring games, managers can identify key success factors, such as effective play strategies or player combinations that contribute to superior results. This insight supports game planning and strategic adjustments, allowing teams to refine their approach for upcoming matches. Additionally, it enables a deeper analysis of player impact, helping managers assess the influence of specific players or play-calling decisions on scoring performance. Furthermore, comparing these high-scoring games against opponents’ performance trends offers valuable competitive benchmarking, revealing strengths to leverage and weaknesses to address.

## Query 3 Highest revenue games by ticket sales- Daniel
![Screenshot](Screen%20Shot%202025-03-14%20at%206.36.29%20PM.png)



### lists the highest revenue games, along with the date, winning team, and the city of the game, by ticket sales/revenue in descending order.To a league manager, the above query results would be useful to evaluate sources of funding, find out what teams or locations encourage engagement, and determine which teams and matchups to advertise and sell broadcast rights to for national TV. Furthermore, the query can be used to help create the season schedule, set appropriate ticket prices, and tailor local marketing strategies in ways that maximize viewership.


## Query 4 Teams with stadium capacity above average
![Screenshot](Screen%20Shot%202025-03-14%20at%209.09.24%20PM.png)
![Screenshot](Screen%20Shot%202025-03-14%20at%209.19.19%20PM.png)





### The information from this query displays the team name, stadium name, and the stadium capacity of the stadium where the capacity of each stadium is greater than the average capacity of all the stadiums. This would be important to managers because they would be able to tell how to set the price of tickets depending on the amount of customers. Thinking even further, they can determine where to host the Super Bowl as the popularity of the stadium and/or game can also be determined from this information.

## Query  5 Players in teams with most wins
![Screenshot](Screen%20Shot%202025-03-14%20at%206.37.25%20PM.png)





### This query retrieves the first name, last name, position, and team name of players who belong to the team with the most wins. This would be important for the NFL because it helps identify key players on the most successful team. Analysts and managers could use this information to study what makes the team successful, whether it be player performance, coaching strategies, or team composition. It could also be useful for marketing and promotional efforts because the league might want to highlight these top-performing players in advertising, media coverage, or award considerations.


## Query  6 Find players in a specific team
![Screenshot](Screen%20Shot%202025-03-14%20at%206.38.28%20PM.png)


### This query selects the name and position of players from a specific team. You can adjust which team you are looking at by changing the team id number. Having the ability to quickly generate a list of players in a specific team can be very valuable to NFL managers. This is critical to roster management, helping managers decide which adjustments need to be made to rosters. This is also important for recruitment, teams can see which positions they need more players for as well as other teams can use this data for negotiations for potential trades. 


## Query  7 Get head coach of each team
![Screenshot](Screen%20Shot%202025-03-14%20at%206.39.00%20PM.png)





### This query finds the head coach for each team by connecting the team and head_coach tables using the coach_id. It shows the team name along with the coach’s first and last name. This is useful for managers because it helps them quickly see who is leading each team. Knowing the head coach for every team makes it easier to track performance, make coaching decisions, and improve communication within the organization. It also helps in planning training, hiring new coaches, or making changes if needed.


## Query 8 lists all players’ names and their teams

![Screenshot](Screen%20Shot%202025-03-14%20at%206.39.23%20PM.png)
### This simple query provides all players’ first and last names along with the team they play for. A league manager can use these findings to look up any player of interest and see which team they play for. Subsequently, the manager can create roster lists, conduct physical investigations or inspections at the desired team practice facility, manage trades and signings, track payroll, and connect performance metrics with a specific player and team.



## Query  9 List all games with stadium information
![Screenshot](Screen%20Shot%202025-03-14%20at%206.39.50%20PM.png)



### The information in this query displays the game ID, the date of the game, the score of the game, the stadium name, and the city the stadium is in. A manager can look at this data and determine where the more higher scoring games took place. WIth this information, ticket prices can be adjusted and it can also show how much revenue/loss to expect in the future games based on the previous games.

## Query 10 Coaches with above-average tenure
![Screenshot](Screen%20Shot%202025-03-15%20at%2011.24.33%20AM.png)



### This query displays the name and tenure of head coaches who have a tenure that is longer than the average of all head coaches. For the league manager this information can be very useful in judging coach performance, conducting investigation into questionable team/coach relationships, deciding who to award (ex. Coach of the Year), and determining which coaches should be marketed more in a way that boosts revenue and engagement with football fans.



# Database Information

![Screenshot](Screen%20Shot%202025-03-14%20at%209.10.05%20PM.png)
















