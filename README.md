# JavaScript-Based-Betting-Game

A simple command-line betting game written in JavaScript where players can deposit money, bet on lines, and spin reels to win based on matching symbols.

# Table of Contents
- [Introduction](#introduction)
- [How to Play](#how-to-play)
- [Installation](#installation)
- [Usage](#usage)
- [Game Rules](#game-rules)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This is a simple betting game created using JavaScript for educational purposes. It allows players to deposit money, bet on multiple lines, and spin reels to try their luck at winning. The game ends when the player's balance reaches zero or they choose to stop playing.

## How to Play

1. The player deposits an amount of money to start the game.
2. The player selects the number of lines to bet on (1-3).
3. The player places a bet per line.
4. The reels spin, and symbols appear on the screen.
5. If symbols on a line match, the player wins based on the symbol value.
6. The game continues until the player runs out of money or chooses to stop.

## Installation

To run this game on your local machine, follow the steps below:

1. Clone the repository:
   ```bash
   git clone https://github.com/M0eiz/JavaScript-Based-Betting-Game.git
   ```
   
2. Navigate to the project folder:
   ```bash
   cd JavaScript-Based-Betting-Game
   ```

3. Install the required dependencies:
   - The game uses `prompt-sync` for user input. Install it using npm:
     ```bash
     npm install prompt-sync
     ```

## Usage

Once you've set up the project, you can run the game using Node.js:

```bash
node index.js
```

## Game Rules

- **Deposit**: Start by entering the amount of money you'd like to deposit.
- **Betting**: Choose how many lines you'd like to bet on (between 1 and 3).
- **Spinning**: Place a bet for each line and spin the reels.
- **Winning**: If all the symbols on a line match, you win based on the symbol's value.
  
### Symbol Values:
- **A**: 5x the bet
- **B**: 4x the bet
- **C**: 3x the bet
- **D**: 2x the bet

### Symbol Counts:
- **A**: Appears 2 times on the reel
- **B**: Appears 4 times on the reel
- **C**: Appears 6 times on the reel
- **D**: Appears 8 times on the reel

The game ends when your balance reaches $0 or if you choose not to play again.

## Technologies Used

- **JavaScript**
- **Node.js** (for running the game)
- **prompt-sync** (for user input)
