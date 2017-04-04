# MahjongScoringAutomater
A small calculator that was built to help the UTS Mahjong society automate their scoring process.

# Purpose of the Program

The UTS Mahjong society records the scoring of their games in an excel spread sheet. At the end of each game people are required to calculate how many points they won and then add those points to their own scores as well as subtract points from the people they played with. Often people would make errors in the adding or scoring of points and these errors wouldn't be found for a few hours or days which would then lead to confusion about who won or lost what points. So I created this app as a way to automate the process and eliminate errors in the scoring and make playing a smoother experience.

# Explanation of How UTS Does Their Scoring

In order to understand this section, the reader needs to understand how Mahjong is played(at least with the Hong Kong version). UTS's scoring system is as follows:
* calculate the points won
* If the winner won by self draw then the points are tripled(i.e. if you won 3 points then self draw makes that 9 points). The winner adds the points to their total score. Then take the original points and subtract that from all the other players total scores (winner gets 9 points and the other players lose 3 points each).
* If the winner won by stealing the tile the points are doubled. The winner adds these points to their total score and the person who they stole the winning tile from loses that many points.

# Explanation of the Scoring Sheet

Each player is listed in the first column and the week they are playing in is listed in the first row. So a player can track their score by each week. At the end of the weeks is the total column which lists the total amount a player has won or lost during the entire semester. Players win points at the expense of other players so the amount of total points present across all players should at all time add up to zero.

As you look at the sheet you will notice zeros below each week. This was a small calculation tool created by one of the society members to make sure that the amount of points taken and added were equal. It adds up the all the numbers during a week and if the final number is negative or positive instead of 0 then everyone knows that too many points were either addded or subtracted. This is further made visible by the far right column called error checking with a very large 0 and the lovely explanation that some society member wrote stating "<--- IF THIS GOES RED WHEN U FINISH, U FUCKED UP".

Below the error checking is a grey button with the text "Open Helper Form". Click on this to open the Scoring Automater Form.

# Guide To Using the Scoring Automater Form

