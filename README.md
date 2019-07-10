
# Welcome to Beanimaled!  
  
Beanimaled is a variation of the famous game, Bejeweled.
  
I implemented:  
- rendering of the grid portion of the Bejeweled-like game;  
> a. The final map/grid **cannot** contain clusters of three or more numbers. If this would happen, rendered grid would already have valid sequences; and the player (possibly) would earn points without interacting with the game board.  
  
>b. The player has to have more than 3 moves after the new grid is rendered. This condition guarantees the player won't see "Game Over" immediately after starting a new game.  
  
- button "New Game" renders new grid.  
  
## Screencast  
  
![](https://media.giphy.com/media/fxHL8QoLL24YFbYqmz/giphy.gif)
  
## Instructions  
  
Download zip file: top left corner of Github, under "Clone or download" button.  
  
Unzip it, go to the folder and open beanimaled.html in your browser, preferably Google Chrome.  
  
Please note, the dependencies have to stay the same as in the original folder.  
  
  
## Future ideas  
  
Ideas for the future, enhancements:  
- instead of generating random numbers for the grid every time, shuffle the fixed/canned pattern of the grid as a starting point.
> I have chosen to generate a grid with random numbers every time the game board is rendered (a). This solution guarantees a higher probability the player will never see the same board again.
> 
> The other option is to have fixed starting pattern which is shuffled every time the board is created.  This solution would introduce a well-balanced board - the number of different tokens would be under control. 
- implement levels  
> I implemented moves counting algorithm which presents the array of arrays of eligible moves. At the beginning of the game, the player must have more than 3 moves. If the game is developed further, it would be great to introduce levels: in the initial state, Level 1 might have from 15 to 25 moves, Level 2 - from 5 to 15 moves, etc.  
- implement the rest of the game  
> clicking on each animal tile, counting coordinates; the player is allowed to move the animal tile when her/his action creates a cluster; implement scoring logics; implement the removal of the cluster and generate new tiles, etc.  
  
## Sources  
- Amazing [animal graphics](https://www.kenney.nl/assets/animal-pac)  
- Flattering [background](https://swapnilrane24.itch.io/nature-background?download)  
Thanks!  