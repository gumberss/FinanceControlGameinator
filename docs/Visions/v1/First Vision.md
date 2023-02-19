## Sign in / Sign up
The main goal of this screen is to allow us to know who is the player. With it, we are going to be able to know what the data from one each player and manage it separately.
It tends to be really simple visually, just providing a way for the player to sign in and sign up to the app, but in terms of the architecture, it tends to be a little more complex.
<img src="https://user-images.githubusercontent.com/38296002/218339483-48a52565-aafa-4faf-a095-53691fd287e0.png" height="600px"/>

## Join a game 
This screen shows to the player the game he has and two buttons, to create a new game or join a new game by the code
<img src="https://user-images.githubusercontent.com/38296002/218339561-9078592c-9863-4cd7-93c4-3ca6438491b6.png" height="600px"/>

## Room (Leader vision)
This screen allows the players to see one each other, also the room leader is able to order the players' turn and start the game
<img src="https://user-images.githubusercontent.com/38296002/218339623-285de27c-8384-48a4-8c78-6fb9081a61b3.png" height="600px"/>

## Room (Player vision)
It should be like the Leader vision of the room, but the players shouldn't be able to order the players' turn.

## Roll the dices
This is the vision of the player when his turn starts
<img src="https://user-images.githubusercontent.com/38296002/218339679-05a82b70-0f1f-4ebf-a7ee-69ce7056721d.png" height="600px"/>

## Buy property
This is the vision of the player when after roll the dices, the player went to a property without owner
<img src="https://user-images.githubusercontent.com/38296002/218339698-fa824cad-2503-472d-b58e-9616a169e549.png" height="600px"/> 

## Pay rent 
This is the vision when the player went to a property with owner
<img src="https://user-images.githubusercontent.com/38296002/218339719-e6c35332-cd99-4b66-8da8-b9975f913147.png" height="600px"/> 

## End turn
This is the vision when the player already done what we should do and now can negotiate or end the turn to make the other player able to play
 <img src="https://user-images.githubusercontent.com/38296002/218339744-887f96ee-1f18-4b19-ada2-c1ce898e04a3.png" height="600px"/>
 
## Wait your turn 
This is the vision when the player needs to wait his turn
<img src="https://user-images.githubusercontent.com/38296002/218339762-6ca54802-8304-422f-9160-368f799f809f.png" height="600px"/> 

## Bank 
This screen allow players to see their properties and negotiate with the bank in their turn. If the player have a hotel and need some money, he needs to sell the hotel before be able to sell the houses, and if the player has only houses, he needs to sell the houses before be able to sell the property.
Additionally, the player is able to sell or mortgage the property. If the player mortgages the property, he won't receive the rent when other player stay there and won't be possible to sell the property too.
Moreover, the player can also borrow money from the bank with interest when:
- The player didn't have two active loans (the quantity could be reviewed when it in development)
- The limit of the amount the player can borrow should be less than 80% of the total value the player have in properties plus houses plus hotel plus money.
- The percentage of the interest increase when the player want to pay in more than 5 installments 
- The limit of the installments should be 10
- The player should be able to pay the installments in advance (with some discount in the interest)
<img src="https://user-images.githubusercontent.com/38296002/218339795-781c820f-a4f0-4b54-9ec7-a81b00f0148d.png" height="600px"/> 

## Investments 
<img src="https://user-images.githubusercontent.com/38296002/218339824-3e7c0d7c-6369-4995-ba30-e26a315b6b83.png" height="600px"/> 

## Notifications 
<img src="https://user-images.githubusercontent.com/38296002/218339848-fe421819-5255-40ed-85e4-d716e615cdb7.png" height="600px"/> 