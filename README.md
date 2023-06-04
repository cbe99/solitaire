# solitaire

Solitaire Game

# game logic && rules

- 52 card deck
- **_The first objective_** is to release and play into position certain cards to build up  
  each foundation, in sequence and in suit, from the ace through the king. The ultimate
  objective is to build the whole pack onto the foundations, and if that can be done, the game is Won.
- **_Rank of cards_**
  The rank of cards in Solitaire games is: K (high), Q, J, 10, 9, 8, 7, 6, 5, 4, 3, 2, A (low).

# basics 1:

_The Deal_
There are four different types of piles in Solitaire:

1. The Tableau: Seven piles that make up the main table.
2. The Foundations: Four piles on which a whole suit or sequence must be built up. In most Solitaire games, the four aces are the bottom card or base of the foundations. The foundation piles are hearts, diamonds, spades, and clubs.
3. The Stock (or “Hand”) Pile: If the entire pack is not laid out in a tableau at the  
   beginning of a game, the remaining cards form the stock pile from which additional cards are brought into play according to the rules.
4. The Talon (or “Waste”) Pile: Cards from the stock pile that have no place in the tableau or on foundations are laid face up in the waste pile.

# basics 2:

- Draw One: With this option, you draw one card from the deck at a time and play with the cards that are revealed.

- Draw Three: With this option, you draw three cards from the deck at a time and play with the topmost card of the three. Once the top card is used or moved to a foundation pile, the next card in the set of three is revealed. This process continues until the deck is empty, and then the process restarts with the remaining cards in the deck.

# code logic:

1. we create a game display first, for the user
2. cards are stacked by alternate colours randomnly in the tableaus and are hidden
   -> number of cards in the tableaus
   1, 2, 3 , 4 , 5 ,6 ,7 = 28 in total tableaus
   -> 24 cards on the stock
3. the end goal is to let the user arrange the cards from King (bottom) >> ace (on top) with alternating colour
4. once done, or maybe directly add the cards of same suit in ace >> King(top) manner in the foundation.

# to run the application

- python -m venv venv
- venv/Scripts/activate
- pip -r requirements.txt
- python game.py
