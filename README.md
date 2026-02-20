# PacMan Game 

A classic PacMan game implementation in Java with enhanced features including ghost AI, scoring system, and smooth gameplay mechanics.

##  Project Overview

This project was developed as part of the Discrete Mathematics course. It demonstrates various discrete mathematics concepts through an interactive PacMan game implementation.

###  Features

- Classic PacMan maze navigation
- Ghost AI with chase behavior
- Score tracking system
- Collision detection
- Multiple game states
- Grid-based movement system

###  Discrete Mathematics Concepts Applied

| Concept | Implementation |
|--------|---------------|
| **Graph Theory** | Ghost and PacMan movement through grid tiles |
| **Set Theory** | HashSet for managing game objects (walls, food, ghosts) |
| **Combinatorics** | Scoring system, lives counting |
| **Boolean Logic** | Collision detection, game state conditions |
| **Probability** | Random ghost direction changes |
| **Finite State Machines** | Game states: Ready → Playing → Game Over |
| **Functions/Relations** | Direction to velocity mapping |
| **2D Arrays/Matrices** | Tile map representation |

## 
How to Run

### Prerequisites
- Java Development Kit (JDK) 8 or higher
- Any Java IDE (Eclipse, IntelliJ, NetBeans) or command line

### Running from Command Line
```bash
# Navigate to src folder
cd src

# Compile
javac PacManGame.java

# Run
java PacManGame
