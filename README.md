# Dicee-Challenge

A simple dice game built with HTML, CSS, and JavaScript that demonstrates DOM manipulation. When you refresh the page, it randomly rolls two dice and declares a winner!

## About the Project

This project is an interactive dice game that showcases the power of **Document Object Model (DOM)** manipulation in JavaScript. The game generates random dice rolls and dynamically updates the webpage content without reloading.

### Implementation Details

- **HTML Structure**: The page consists of two dice containers, each with a player label and dice image.
- **DOM Manipulation**: JavaScript is used to:
  - Generate random numbers (1-6) for each dice
  - Dynamically update dice images using `document.querySelector()`
  - Change the heading text to announce the winner
- **CSS Styling**: Custom styles for dice layout, responsive design, and engaging visuals

### Key DOM Methods Used

```javascript
// Selecting elements
document.querySelector();
// Modifying content
element.innerHTML;
// Changing attributes
element.setAttribute();
```

## Features

- Random dice roll for two players
- Dynamic image updates based on roll results
- Automatic winner declaration
- Responsive design that works on all devices
- Simple and clean UI

## How to Play

1. Open `index.html` in your browser
2. Click refresh or press F5 to roll the dice
3. The heading will automatically update to show the winner

## File Structure

```
Dicee-Challenge/
├── index.html      # Main HTML file
├── style.css       # Styles for the game
├── index.js        # Game logic and DOM manipulation
└── images/         # Dice images (dice1.png to dice6.png)
```

## Deployment

This project is ready for deployment on Vercel. All file paths are relative (start with `./`).

---

Created by Charan-Tj.
