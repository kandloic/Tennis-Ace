# Tennis-Ace
Tennis-Ace is an ML model that predicts the outcome of a tennis player based on data provided by the Association of Tennis Professionals (ATP)

The ATP men’s tennis dataset includes a wide array of tennis statistics, which are described below:

## Identifying Data
**Player:** name of the tennis player
<br>
**Year:** year data was recorded
## Service Game Columns (Offensive)
**Aces:** number of serves by the player where the receiver does not touch the ball <br>
**DoubleFaults:** number of times player missed both first and second serve attempts <br>
**FirstServe:** % of first-serve attempts made <br>
**FirstServePointsWon:** % of first-serve attempt points won by the player <br>
**SecondServePointsWon:** % of second-serve attempt points won by the player <br>
**BreakPointsFaced:** number of times where the receiver could have won service game of the player <br>
**BreakPointsSaved:** % of the time the player was able to stop the receiver from winning service game when they had the chance <br>
**ServiceGamesPlayed:** total number of games where the player served <br>
**ServiceGamesWon:** total number of games where the player served and won <br>
**TotalServicePointsWon:** % of points in games where the player served that they won
## Return Game Columns (Defensive) 
**FirstServeReturnPointsWon:** % of opponents first-serve points the player was able to win <br>
**SecondServeReturnPointsWon:** % of opponents second-serve points the player was able to win <br>
**BreakPointsOpportunities:** number of times where the player could have won the service game of the opponent <br>
**BreakPointsConverted:** % of the time the player was able to win their opponent’s service game when they had the chance <br>
**ReturnGamesPlayed:** total number of games where the player’s opponent served <br>
**ReturnGamesWon:** total number of games where the player’s opponent served and the player won <br>
**ReturnPointsWon:** total number of points where the player’s opponent served and the player won <br>
**TotalPointsWon:** % of points won by the player
## Outcomes
**Wins:** number of matches won in a year <br>
**Losses:** number of matches lost in a year <br>
**Winnings:** total winnings in USD($) in a year <br>
**Ranking:** ranking at the end of year
