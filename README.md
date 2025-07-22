# Realistic-Card-Shuffling
Realistic Shuffle Simulation
This Java program simulates a realistic riffle shuffle of a standard deck of playing cards, performing three consecutive shuffles and displaying the result.

Features
Creates a standard 52-card deck with suits (hearts, clubs, diamonds, spades) and values (Ace through King)

Implements a realistic riffle shuffle algorithm that:

Cuts the deck approximately in half with slight variation (±2 cards)

Interleaves cards from each half in small groups (0-2 cards at a time)

Performs three consecutive riffle shuffles

Outputs the shuffled deck

How It Works
Deck Creation: The program starts by creating a standard deck of 52 cards with proper suit symbols (♥️, ♣️, ♦️, ♠️).

Shuffling Process:

The deck is split into two approximately equal halves with slight random variation

Cards are interleaved from each half in small random groups (0-2 cards at a time)

This process is repeated three times to simulate a realistic shuffle

Output: The final shuffled deck is printed to the console

Usage
Simply run the program to see the result of three riffle shuffles:

bash
javac RealisticShuffle.java
java RealisticShuffle
Example Output
text
RIFFLE SHUFFLED DECK:
[6♥️, 7♥️, 4♣️, 5♣️, 8♥️, 9♥️, 6♣️, 7♣️, 10♥️, J♥️, 8♣️, 9♣️, Q♥️, K♥️, 10♣️, J♣️, A♦️, 2♦️, Q♣️, K♣️, 3♦️, 4♦️, A♠️, 2♠️, 5♦️, 6♦️, 3♠️, 4♠️, 7♦️, 8♦️, 5♠️, 6♠️, 9♦️, 10♦️, 7♠️, 8♠️, J♦️, Q♦️, 9♠️, 10♠️, K♦️, A♥️, J♠️, Q♠️, 2♥️, 3♥️, K♠️, A♣️, 4♥️, 5♥️, 2♣️, 3♣️]
Customization
You can modify the program by:

Changing the number of shuffles (adjust the loop count in main)

Adjusting the randomness parameters in the riffleShuffle method

Adding additional shuffle types for more variety

Requirements
Java 8 or later
