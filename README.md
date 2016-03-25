# Python functions to implement a Swiss-system tournament

## Install

### Initialising the database

Open PostgreSQL
> psql

Run the tournament.sql script to create the tournament database, tables and views
> \i tournament.sql

### Available functions
1. deleteMatches()
2. deletePlayers()
3. countPlayers()
4. registerPlayer(name)
5. playerStandings()
6. reportMatch(winner, loser)
7. swissPairings()


### Testing the functions

Run the tournament_test.py Python file to test the tournament functions.
> python tournament_test.py
