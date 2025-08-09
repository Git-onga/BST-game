# Binary Branch: The Tree of Numbers

This project is an interactive Binary Search Tree (BST) game implemented in JavaScript. The main logic is in [`index.js`](index.js), which powers the game UI and modes.

## Features

- **Visual BST Generation:** Generates and displays a random or balanced BST using SVG.
- **Game Modes:**
  - **Insert Mode:** Insert a given number at the correct position in the BST.
  - **Guess Parent:** Guess which node would be the parent for a given number.
  - **Fix the Tree:** Swap nodes to restore BST validity after intentional corruption.
- **Difficulty Levels:** Choose tree depth (Easy, Medium, Hard, Expert).
- **Scoring System:** Earn or lose points based on correct or incorrect actions.
- **Responsive UI:** Interactive SVG visualization and controls.

## How It Works

- The game initializes a BST based on the selected difficulty.
- Users select a mode and interact with the tree by clicking nodes.
- The tree updates visually and provides feedback and scoring.

## File Structure

- [`index.js`](index.js): Main JavaScript logic for the game.
- [`index.html`](index.html): Main HTML file for the game UI.
- [`index.css`](index.css): Styles for the game UI.

## Usage

1. Open [`index.html`](index.html) in your browser.
2. Select a game mode and difficulty.
3. Follow the prompts and interact with the tree.

## Customization

- You can adjust the difficulty options in the `setupDifficultySelector` function.
- Game logic for each mode is in the respective handler functions (`handleInsertMode`, `handleGuessParentMode`, `handleFixTreeMode`).
