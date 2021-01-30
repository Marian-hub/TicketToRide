# GAME RULES 
There is a simple menu  that gives the player two possibilities:<br/>
- Every player can create a new game and host host it on the server.
- The other players will see if the game is active and can try to join the newly create game if the game has not yet started and if the game creator allows him to join the game.

## player
- Initially there are just 2 players that alternate each other in the webpage . later there will be N players 
- There is a table with at least 10 cities connected to each other with a railwayline
- Every railway line can be just of these colors red,blu , yellow, orance , green , black
- Every railway has to have a minimum of 3 wagons and a maximum 6 

## deck of cards
- There is deck of cards that is shuffled at the start of the game with  78 cards og 6 different colors:<br/>
    - 13 red cards
    - 13 blu cards
    - 13 yellow cards
    - 13 green cards
    - 13 black cards

- At the start of the game every player takes 4 cards randomly from the deck
- At the start of the game 5 cards are randomyl picked and positioned face up  so everyone can see them

## player actions
During his turn the player can perform one of these three actions:
- ** Pick faced up cards **:<br/>
The player can choose 2 of the 5 faced up cards and take them as his, then there will be randomly picked another 2 cards so there will always be 5 faced up cards.
- ** Pick a card **:<br/>
The  player picks the first 2 cards on top of the deck of cards
- ** Create a new line **:<br/>
If the player can decide to create a new railway line, if the line has N wagons he would have to use N cards of the same color of the same line to create the create the new railway line. If the player does not have enought cards he can abort the operation and do  something else.

## Scoreboard 
Every time that a player creates a new railway line he gets points depending on the railway line
- length 3  -> points 3
- length 4  -> points 5
- length 5  -> points 7
- length 6  -> points 10

## Winning 
When the last card of the deck has been picked the player with the most points wins the game