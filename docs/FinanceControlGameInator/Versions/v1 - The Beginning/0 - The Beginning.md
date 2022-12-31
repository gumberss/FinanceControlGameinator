## Vision
The vision of this version is to make the players control their money in a simple way, this version does not have any integration between the apps neither with the server, the game is going to be played based in the trust of the players.

## Objective
- Play Monopoly game without using the money with a simple system architecture
- Create the initial architecture of the mobile app

## How
- [[3 - Start Game Control|Creating an initial setup of the game]]
- [[1 - Accounts |Creating Accounts]]
- [[2 - Transactions|Allowing Transactions]]

## Limits

### Business 
- When the player is not able to pay the amount necessary to the other player, this player is considered bankrupt

### Technical
- The game is going to be stateless, so if the player close the app, the game will restart for him
- If the player went bankrupt and all the players want to restart the game, close the app and reopen makes the game restart 
- If a player close the app accidentally, and remember how much money he had, just make an operation including the money again
- If the player close the app accidentally, and don't remember how much money he had, the player should add the money the other players allow

## Is this version useful?
- From the point of view of business, actually, no, the calculator app in android mobile do a better job, but this version let me focus on the mobile app architectural part and in the GitHub setup.