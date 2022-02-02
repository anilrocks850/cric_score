# cric_score
Code was written in " cric_score.py " file.
updating scores match by match,
by using match wise ball by ball data in csv format,I created stats of each player from https://cricsheet.org/downloads/.
Intially I took only ODI matches played by India,
By executing we will see match wise highlights includes,50's,100's,wickets,landmarks achieved in that match and landmarks that are gonna be achieved by specific player
I took data of 3 matches and put another match as in comments for testing.
from lines from 21 to 42:
    #line[2] is country name ,line[3] is player name in csv file, which are in csv file from line 21
    #country_dict is teams containing player's names and their performance in this particula match
    #players_dict contains all players and their total performance cumulative of performance in all the matches each player had played
from lines from 69 to end:
    #line[3] is country name ,line[4] is player name who is in strike for this particular ball
    #line[6] is bowler who  bowled that ball
    # line[7] is runs scored on this ball,line[8] is runs in extras on this ball