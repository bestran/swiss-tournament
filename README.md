# Python functions to implement a Swiss-system tournament

## Install

### Initialising the database

Open PostgreSQL
  psql

Run the tournament.sql script to create the tournament database, tables and views
  \i tournament.sql

### Available functions
1. `deleteMatches()` - Remove all the match records from the database.
2. `deletePlayers()` - Remove all the player records from the database.
3. `countPlayers()` - Returns the number of players currently registered.
4. `registerPlayer(name)` - Adds a player to the tournament database.
5. `playerStandings()` - Returns a list of the players and their win records, sorted by wins.
6. `reportMatch(winner, loser)` - Records the outcome of a single match between two players.
7. `swissPairings()` - Returns a list of pairs of players for the next round of a match.


### Testing the functions

Run the tournament_test.py Python file to test the tournament functions.
> python tournament_test.py
