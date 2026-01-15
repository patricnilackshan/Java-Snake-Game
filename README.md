# Snake Game

A classic Snake game implementation in Java using Swing.

## Description

Implemented core game mechanics including snake movement, collision detection, apple spawning, and score tracking.
Designed object-oriented architecture with separate classes for game logic (GamePanel), window management (GameFrame), and application entry point (SnakeGame).
Created a GUI-based user interface using Java Swing with real-time rendering and smooth keyboard controls.
Integrated game state management for handling running/game-over states with automatic restart functionality.
Implemented gameplay features including directional movement validation, self-collision detection, and boundary checking.

## Features

- Classic snake gameplay
- Score tracking
- Game over screen with restart functionality
- Smooth graphics and controls

## How to Play

- Use arrow keys to control the snake's direction
- Eat the red apples to grow and increase your score
- Avoid hitting the walls or your own body
- Press any key after game over to restart

## Running the Game

### Option 1: Run the executable JAR file
```bash
java -jar SnakeGame.jar
```

### Option 2: Compile and run from source
```bash
# Compile
javac -d bin src/com/patric/*.java

# Run
java -cp bin com.patric.SnakeGame
```

## Building from Source

To build the executable JAR file:

```bash
# Compile the source files
javac -d bin src/com/patric/*.java

# Create the JAR file
cd bin
jar cvfm ../SnakeGame.jar ../MANIFEST.MF com/patric/*.class
```

## Requirements

- Java Runtime Environment (JRE) 8 or higher

## Project Structure

```
Snake/
├── src/
│   └── com/
│       └── patric/
│           ├── SnakeGame.java      # Main entry point
│           ├── GameFrame.java      # Game window
│           └── GamePanel.java      # Game logic and rendering
├── bin/                            # Compiled classes
├── MANIFEST.MF                     # JAR manifest file
├── SnakeGame.jar                   # Executable JAR
└── README.md                       # This file
```

## License

This project is open source and available for educational purposes.
