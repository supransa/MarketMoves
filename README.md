# MarketMoves
Objective: From historical data find how the stock market/an instrument has moved and identify trends.

Intro:
1. Market has 3 moves; Up, Down and Consoldated moves. This script adds 3 more moves Whipsaw(when market is choppy or moves are greater than 2 standard deviations in a given period), UpWhipsaw and DownWhipsaw. 
2. Step and Delta represent the period of move and percentage of move to search. The moves/output will vary depends on these values. We need a period and the percent of move to indetify or extend a trend.
3. UpWhipsaw and DownWhipsaw are choppy moves after Up/Down trend.
4. Script takes yahoo finance data and walks through end of day Close data to find out the moves.
5. All the moves identified are returned as a dataframe with start and end time of a move along with the percentage move. 
