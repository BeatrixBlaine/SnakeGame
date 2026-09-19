# Snake Game

A classic Snake game built with **Java Swing** as a practical project for learning Java programming, GUI development, game loops, and basic game logic.

## Overview

The game recreates the classic Snake experience where the player controls a growing snake, collects food, and tries to achieve the highest possible score without colliding with the game boundaries or the snake's own body.

The project was built from scratch using Java and Swing.

## Features

* Classic Snake gameplay
* Real-time keyboard controls
* Snake movement and growth
* Random food generation
* Collision detection
* Score tracking
* Game-over handling
* Graphical user interface using Java Swing

## Tech Stack

* **Java**
* **Java Swing**
* **Object-Oriented Programming**
* **IntelliJ IDEA**

## Game Structure

The game is built around a simple game loop:

```text
Start Game
    ↓
Read Player Input
    ↓
Move Snake
    ↓
Check Food Collision
    ↓
Grow Snake / Update Score
    ↓
Check Wall & Body Collision
    ↓
Game Over?
   ↙     ↘
 Yes      No
 ↓         ↓
End      Continue
           │
           └──────→ Game Loop
```

## Concepts Practiced

This project helped reinforce several Java fundamentals:

* Classes and objects
* Encapsulation
* Methods
* Arrays and collections
* Loops
* Conditional logic
* Random number generation
* Event handling
* Keyboard input
* GUI programming with Swing
* Timers and game loops
* Collision detection

## Running the Game

### Prerequisites

* Java Development Kit (JDK)
* IntelliJ IDEA or another Java IDE

### Using IntelliJ IDEA

1. Clone the repository:

```bash
git clone https://github.com/BeatrixBlaine/SnakeGame.git
```

2. Open the project in IntelliJ IDEA.

3. Locate the main Java class inside `src`.

4. Run the application's `main` method.

## Project Purpose

This project was created as a hands-on Java programming project to move beyond basic exercises and apply programming fundamentals to a complete interactive application.

Building the game provided practical experience with **object-oriented programming, event-driven programm**
