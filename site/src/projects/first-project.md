---
title: BlackJack 
emoji: 🎰
metaDescription: Blackjack Game 
date: 2019-01-01T00:00:00.000Z
summary: Program to have Blackjack game run in terminal. 
tags:
  - Python
---
https://github.com/pkelly55/Blackjackgame
### Task

Run Blackjack on the terminal.
### Solution

Starting with my card variables, are set up as strings for the print and display of the game. Once all the cards have been set up correctly as separate entities under the suits and rank variables. Then once those cards are set up it comes time to set a value for each card. This is done in a dictionary called values in my code. Setting up the Ace card as 11 is normal and is adjusted later in the code.
Beginning to set up my first class is the card class, which is an abstract class that is only trying to set up the proper output of the display. Throughout my code is the idea of polymorphism because, in most of my classes, I am using def __init__ to set variables in my classes and methods. Having polymorphism within my code gives me the ability for it to be adaptable to what I want to do with the game. I can change certain variables without having to change any of the actual implementations because they will all be changed in the above abstract methods.
Then it comes to all the cards rather than individual ones, my deck class sets up all the cards in a deck of 52 cards. This adds to the randomness of the shuffle and no games being the same. This involves the __str__ and __init__ methods to append all the cards in the deck using the for loop with ranks. Within this class is the deal function because the cards must come out of the deck to be dealt. Using the pop function within dealing the cards means that there are only 52 cards in the deck so no cards will repeat. Dealing cards one time will return the single card that is pulled out of the deck by the computer. Having 52 cards means there are almost an infinite amount of ways the cards can be dealt. This gives what I would say makes the game so special the luck and randomness that one needs to get to twenty-one.