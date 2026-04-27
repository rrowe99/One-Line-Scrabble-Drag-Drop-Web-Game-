# One-Line Scrabble

An interactive Scrabble-style web game built using HTML, CSS, JavaScript, and jQuery UI. Players drag and drop letter tiles onto a single-row board to form valid words and score points based on standard Scrabble rules.

---

## Live Demo
https://rrowe99.github.io/GUI-HW5/

---

## Features
- Drag-and-drop tile placement using jQuery UI  
- One-line Scrabble board with bonus squares  
- Double Letter and Double Word scoring  
- Real-time score calculation  
- Adjacency validation (tiles must be placed next to each other)  
- Tile rack that refills after each move  
- Restart button to reset the game  

---

## How It Works
- Tiles are randomly generated based on Scrabble letter distribution :contentReference[oaicite:0]{index=0}  
- Players drag tiles from the rack onto board squares  
- The game checks if placements are valid (adjacent tiles only) :contentReference[oaicite:1]{index=1}  
- Score is calculated using letter and word multipliers  
- After submission, tiles are cleared and new ones are dealt  

---

## Project Structure
- index.html → game layout and structure :contentReference[oaicite:2]{index=2}  
- style.css → styling for board, tiles, and layout :contentReference[oaicite:3]{index=3}  
- scrabble.js → game logic (drag/drop, scoring, validation) :contentReference[oaicite:4]{index=4}  
- Scrabble_Pieces_AssociativeArray_Jesse.js → tile values and distribution :contentReference[oaicite:5]{index=5}  

---

## Example Gameplay
- Drag tiles from the rack onto the board  
- Form a valid word using adjacent tiles  
- Click "Play Word" to calculate score  
- Tiles reset and new ones are dealt  

---

## What I Learned
- Implementing drag-and-drop interfaces using jQuery UI  
- Managing game state and user interaction in JavaScript  
- Designing scoring systems with multiple conditions  
- Validating user input and enforcing game rules  

---

## Technologies Used
- HTML  
- CSS  
- JavaScript  
- jQuery  
- jQuery UI  

---

## Author
Richard Rowe  
University of Massachusetts Lowell  
