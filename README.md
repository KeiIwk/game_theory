# Game Theory Simulation Program

## Overview
This Python program simulates a pricing strategy game based on game theory concepts. The program offers two modes: one where the user competes against the computer and another where two automated players (User1 and User2) compete over multiple rounds. The game models a scenario in which business competitors decide whether to keep or decrease their prices, with payoffs dependent on their choices.

## Features
1. **User vs. Computer Mode**  
   - The user can choose to play against the computer.  
   - The game rules and profit matrix are explained at the beginning.  
   - The computer's choice is randomized, and the outcome determines the payoffs.  
   - The game declares a winner based on the points scored.

2. **Automated Players Mode**  
   - When the user opts not to play, two automated players (User1 and User2) simulate the game over five rounds.  
   - User2 employs a "tit-for-tat" strategy, adjusting its decisions based on User1's previous actions.  
   - Each round's results are displayed, and a final winner is declared based on the total score.

## Program Workflow
1. **User Interaction**  
   - Prompts the user to decide whether to play.  
   - If playing, asks for the user's name and strategy choice.  

2. **Error Handling**  
   - Ensures valid inputs for game participation and strategy selection.

3. **Game Simulation**  
   - In **User vs. Computer Mode**, the computer makes random choices.  
   - In **Automated Players Mode**, User1's choices are randomized, and User2 employs a strategy based on User1's behavior.

4. **Scoring and Results**  
   - Points are allocated based on the profit matrix.  
   - After each round, scores are displayed, and a final winner is determined.
