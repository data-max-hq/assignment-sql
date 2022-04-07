# Assignment SQL

## Database Design Task
Design a database schema for the Football World Cup. The requirements are these:
1. There are 32 teams.
2. Each team has a name, number of players, confederate, and coach.
3. Each confederate has a name, and a continent's name.
4. A match is played between two team, and has a stadium, goals_host, goals_guest, and the stage on which the game was played. goals_host is the number of goals the host team scored in this match, and the goals_guest is the number of goals the guest team scored.
5. A stadium has a city, a name and capacity.
6. Possible stages are: Group stage, 1/16, Quarter finals, Semi finals, Small final and Final.

Please provide a database schema for this task.

# SQL Query Task
Write a query that for every match returns: the team names, the stage name and the result in words, e.g: If the final match was between France and Croatia, result was 4 goals for France and 2 goals for Croatia it should return this:

| Team Host  | Team Guest  | Stage  | Result  |
|------------|-------------|--------|---------|
| France     | Croatia     | Final  | Win Host|

If guest team won, prit Win Guest as Result, otherwise print Draw.