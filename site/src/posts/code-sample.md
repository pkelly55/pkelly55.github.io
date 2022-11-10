---
title: Code from Blackjack
metaDescription: Add code samples to your markdown files
date: 2019-01-01T00:00:00.000Z
summary: Summary of Blackjack
tags:
  - blackjack
  - python
 
---
## Deck code snippet

Creating the deck to pop a single card.

```python
class Deck:
    
    def __init__(self):
        self.deck = []  # start with an empty list#
        for suit in suits:
            for rank in ranks:
                self.deck.append(Card(suit, rank))
    
    def __str__(self):
        deck_comp = '' 
        for card in self.deck:
            deck_comp += '\n' + card.__str__() #add each card objects string
        return 'The deck has' + deck_comp
            
    def shuffle(self):
        random.shuffle(self.deck)
        
    def deal(self):
        single_card = self.deck.pop()
        return single_card

```
