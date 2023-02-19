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

Also, there is the start game control feature, in this version. Every time the app in opened, the start game control will run and give the initial amount of money the player needs to start the game
<img src="https://user-images.githubusercontent.com/38296002/219982177-9aca1201-0543-4fbb-bd52-6211188b0ac0.png"/>

As we mentioned before, this version is not about delivering only features from the business perspective, but there are much value to be delivered in the technical too. This is the start point of the mobile app, so we want to create it in the right way, thinking not only of now, but in how we can create an architecture for the future, in an evolutionary way, iterative and incremental. 
In my point of view, one of the biggest problems in the software development is the need to deliver business value in a short period of time. I know, sometime it is necessary, but everything in software development is a trade-off, and we want to go in the right way, with a high quality. 

<img src="https://user-images.githubusercontent.com/38296002/219974586-f84ca5e4-560d-47bc-b6db-52514ac08a66.png"/>

At this version, we want to create the initial standardization, folder structure, component creation and also exploring some tests in the client side, since this version doesn't have the server side. Creating a clean code with a good architecture, tests, well-structured and with the right components, generate a system with high level of maintainability, enabling to deliver new features faster in the long run.

Thinking in the long run, this version will have some components that can be reused in the future.:
- Current account Balance will be turned to player details;
- Spend and receive buttons can be turned to card buttons like "Borrow money";
- Cancel and Confirm buttons can already be the cancel and confirm buttons;
- The popup of amount to spend/receive money can already be a simple version of a popup component.

## Limitations

- We don't expect this version to have interaction between players
- We don't expect this version to have the state of the player's account persisted in the client side
- We don't expect his version to have interaction with the back end

## References 
- https://martinfowler.com/articles/is-quality-worth-cost.html
- https://stackoverflow.blog/2021/10/18/code-quality-a-concern-for-businesses-bottom-lines-and-empathetic-programmers/