# project2
fsd_nanodg: project materials
This project contains the code for udacity full-stack developer nanodegree course
It contains the following:
   create_tournament - a courtesy script for creating the tournament db
   delete_tournament - a courtest script for deleting the tournament db
   tournament.py - a python module containing following fuctions:
       connect - uses psycopg2 to initialize a connection to the tournament db
       deleteMatches - clears match data from the matches table
       deletePlayers - clears player data from the players table
       countPlayers - returns a count of players in the players table
       registerPlayer - registers player data in the players table; accepts one string input variable: myname
       playerStandings - records player standings in the player standings table
       reportMatch - records match outcome data; accepts two input variables winner and loser 
       swissPairings - returns ordered pairs of players by id and name aligned by matches won

Note: Resulst of Confirmed Test can be found in test_results.txt
