---
title: Blackjack Terminal Game
emoji: 🎰
metaDescription: Python-based Blackjack game with object-oriented design
date: 2019-01-01T00:00:00.000Z
summary: An interactive terminal-based Blackjack game built with Python, featuring object-oriented programming principles and randomized card dealing.
tags:
  - Python
  - Object-Oriented Programming
  - Game Development
---

[View on GitHub](https://github.com/pkelly55/Blackjackgame)

## 🎯 Project Overview

A fully functional Blackjack game that runs in the terminal, built using Python and object-oriented programming principles. The game simulates a real casino Blackjack experience with proper card dealing, scoring, and game flow.

## 🚀 Key Features

- **Authentic Gameplay**: Full Blackjack rules implementation including dealer behavior and scoring
- **Randomized Card Dealing**: Shuffled 52-card deck with no card repetition
- **Object-Oriented Design**: Clean class structure with Card, Deck, and game logic separation
- **Terminal Interface**: Simple, intuitive command-line interface for gameplay

## 🛠️ Technical Implementation

### Core Architecture

The game is built around three main classes:

**Card Class**: Abstract class handling individual card representation with proper display formatting

**Deck Class**: Manages the 52-card deck with shuffling and dealing functionality
- Uses list operations to ensure no card repetition
- Implements random shuffling for game variety
- pop() method for realistic card dealing

**Value System**: Dictionary-based card values with dynamic Ace handling (1 or 11)

### Key Design Patterns

- **Polymorphism**: Utilized `__init__` methods across classes for flexible variable management
- **Abstraction**: Clean separation between card representation and game logic
- **Encapsulation**: Self-contained methods for dealing, scoring, and game flow

### Technical Highlights

```python
# Card dealing uses pop() to ensure no repetition
def deal(self):
    return self.deck.pop()

# Dynamic Ace value adjustment based on hand total
# Ensures players don't bust when Ace can count as 1
```

## 💡 What I Learned

- **Object-Oriented Programming**: Deepened understanding of classes, inheritance, and polymorphism
- **Game Logic**: Implemented complex rules and state management
- **Code Organization**: Structured code for maintainability and extensibility
- **Algorithm Design**: Created efficient card shuffling and dealing mechanisms

## 🎲 Gameplay

Players compete against the dealer to reach 21 without going over. The game handles:
- Initial card dealing (2 cards each)
- Hit/Stand decisions
- Dealer behavior (hits on 16, stands on 17)
- Win/Loss/Tie determination
- Proper Ace value adjustment

## 🔗 Technologies Used

- **Language**: Python
- **Concepts**: Object-Oriented Programming, Data Structures, Algorithms
- **Design Patterns**: Abstraction, Polymorphism, Encapsulation

---

*This project demonstrates my ability to translate real-world systems into code using proper software engineering principles.*
