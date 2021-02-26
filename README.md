# Gully_cricket_app.cpp

Using c++ language we build a mini cricket application named Gully Cricket App.


Project Requirements
  1. There should be two teams: TeamA and TeamB
        a. Each team will have 3 players
        b. The player names will not be entered by the user. You can assign names to the players yourself.
  
  2. There should be two innings
        a. Each inning will be of 6 balls (one over)
              i. In each inning, one batsman from the batting team will bat for 6 balls and one bowler from the bowling team will bowl 6 deliveries
              ii. One batsman from the batting team and one bowler from the bowling teamwill be selected randomly for each inning
        b. TeamA will always bat first which means TeamB will always bowl first
 
  3. In each delivery, runs can be scored from 0 to 6
 
  4. There will be no criteria to get wickets. In simple words, once a batsman starts his inning, he will bat for all the 6 balls without getting out/dismissed/retired hurt etc
  
  5. After completion of two innings i.e. after each team has done batting, scored runs will be compared to decide the winner or to decide if there is a tie.



  The match will conclude only after each batting team has faced 6 deliveries. In the second inning, at any point of time during the match, if the score of TeamB is greater than the runs scored  by TeamA (in the first inning) then the match should not end. The match should continue until TeamB has faced all the 6 deliveries. 
