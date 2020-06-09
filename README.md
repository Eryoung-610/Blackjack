# Blackjack
(Insert link here)

## Setting up project
• Clone or download

## About the game
Designed to be a one player game against the AI dealer, where the player attempts to beat the dealer by getting a count as close to 21 as possible, without going over 21. Utilize the hit/stand functions to make your decisions. 

## Wireframe
![Wireframe](https://github.com/Eryoung-610/Blackjack/blob/master/BlackjackWireframe.JPG)

## Tech Being Used
* HTML/CSS/JS
* Bootstrap

## Minimum Viable Product
* Establish table (HTML/CSS)
  * General casino table (The green felt ones)

* Establish a deck of cards (JS) --> Look up deck of cards api.
  * Values [2-Ace].
  
* Turn system(JS)
  * Implement delay on dealer decisions
  * Disable hit/hold buttons when not user turn
 
* Shuffle Deck (JS)
  *Push into temp array, push back into original array

* Deal Hand (JS)
  * Pop from deck of card array to user
  
* Basic blackjack functions (HTML/CSS/JS)
  * Hit, Hold

* Winning Conditions
  * if (playerSum >= 21) endGame, else turn()
 
## Strech Goals

* Implement chip/money system

* Card Suits?

## Run down

* On load
  * No cards dealt, deck is initialized.
  * Button displayed to deal hand
  
* On dealed hand
  * 2 Popped card objects from array to user
  * 1 hidden card and 1 visible card dealt to dealer
  * Hit and hold/stand button displayed when user turn.
  
* On hit
  * Deal new card
  * Array should be updated
  * if playerSum >= 21, call winner/endGame
  
* On hold/stand
  * if dealerSum < playerSum, dealer draws cards until conditional is false
  * Determine winner
  
* On winner found
  * Hide stand/hit buttons
  * Declare winner
  * Deal button reappears as a way to repeat game

## Roadblocks

*
