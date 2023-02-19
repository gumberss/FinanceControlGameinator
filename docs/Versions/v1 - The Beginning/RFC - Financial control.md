## Context

One of the better games I've ever seen is Monopoly, the purpose of this game is to remain financially solvent while forcing opponents into bankruptcy. This game has some features that make the players build a strategy to be financially stable for as much as possible.
There are many things that can be automated in this game, from financial control to the board, and after it, many other features could be added making the game more interesting than it already is. 
We elaborated a first version of the app vision, and you can check it [[First Vision|here]]. How you can see, there are an ambitious future, with many functionalities, with some of them not even existent in the Monopoly game and all of them are going to be automated, full controlled by the app. But of course, everything has a start point.

## Goals
We're going to create the first version of the app, allowing the players to manage their accounts, been able to spend money and receive money in the game.
With this version, we expect to achieve these goals:
- Removing the necessity to use the physical money;
- Removing the necessity to one player be the bank;
- Removing the necessity to distribute the initial money to each player;
- Create the standardization of the app

To achieve these goals, we're going to create a mobile app that manage the player account, allowing the player to add money to and remove it from the account

## Approach
The main actions the player can do with his account in the game are:
- Receive money from the bank (like a luck card or when the player complete a cycle in the board)
- Buy a property from the bank;
- Pay the bank (like when the player needs to play the Federal Revenue Service or find a setback card);
- Pay rent to other players;
- Buy properties from other players;
- Buy special cards from other players (i.e. Habeas Corpus);
- Buy houses and hotels;
- Sell houses and hotels;
- Sell properties to the bank;
- Sell properties to other players;
At this version, we don't want to know what kind of operation the player is making neither if the negotiation is with other player or the bank, the main idea is to handle the money the player have, so the player is going to inform to the app if he is receiving some money or if he is spending some money and that is it for now.
The image below present how this version is going to work. As you can see, this version is pretty simple, it presents to the player the amount of money he has and two possible actions, spend some money and receive some money.
<img src="https://user-images.githubusercontent.com/38296002/210139844-2346e33f-a529-40f6-b238-4e339462a84c.png"/>

As we mentioned before, this version is not about delivering only features from the business perspective, but there are much value to be delivered in the technical too. This is the start point of the app, so we want to create it in the right way, thinking not only of now, but in how we can create the app for the future, in an evolutionary way, iterative and incremental. 
In my point of view, one of the biggest problems in the software development is the need to deliver business value in a short period of time. I know, sometime it is necessary, but everything in software development is a trade-off.


## Limitations

- We don't expect this version to have interaction between players
- We don't expect this version to have the state of the player's account persisted in the client side
- We don't expect his version to have interaction with the back end
