# Nyan Cat OOP Game

<p align="center"><img src="./images/screenshot.png"></p>

# Introduction

I've created a Nyan Cat-themed Object Oriented Programming (OOP) game as a personal project to deepen my understanding of OOP principles. In this game, players navigate a cheeseburger character to avoid Nyan Cats raining from the sky.

## Game Description

**I CAN HAZ CHEEZBURGER?!??** is the name of this quirky game. The player controls a cheeseburger character, moving left or right using keyboard arrows. The goal is to avoid Nyan Cats and survive as long as possible to score higher.

## Technical Implementation

- **JavaScript OOP**: The game is built using JavaScript with a focus on object-oriented principles, ensuring a structured and scalable codebase.
- **Collision Detection**: Implemented collision detection to end the game when the player collides with a Nyan Cat, using JavaScript techniques and constants like `ENEMY_HEIGHT` and `PLAYER_HEIGHT`.
- **Game Customizations**: Added several features to enhance gameplay, including new characters, enemies, and a dynamic gameboard.

## Assignment Challenges

1. **Collision Logic**: Modified the `isPlayerDead` function in the `Engine` to accurately detect collisions between the player and enemies.
2. **Game Enhancements**: 
   - Added major changes like a scoring system and increasing difficulty levels over time.
   - Implemented minor changes such as new game characters, background music, and a restart button.

## Conclusion

This Nyan Cat OOP Game showcases my proficiency in applying object-oriented programming concepts in a fun and interactive project. It highlights my ability to implement complex game mechanics like collision detection and dynamic difficulty adjustment.

## Useful Links

- [Keyboard Events](https://javascript.info/keyboard-events)
- [2D Collision Detection](https://developer.mozilla.org/en-US/docs/Games/Techniques/2D_collision_detection)
- [Element.getBoundingClientRect](https://developer.mozilla.org/en-US/docs/Web/API/Element/getBoundingClientRect)
- [JSRef Met Element getBoundingClientRect](https://www.w3schools.com/jsref/met_element_getboundingclientrect.asp)

## Glossary

- **Engine**: Core environment that powers the game, implemented in `Engine.js`.
- **Hitbox**: The physical space an entity occupies, crucial for collision detection.
- **Gameplay**: The rules and interactive elements that define the player's experience.
- **Gameboard**: The visual area where the game action takes place.
