# Flappy Bird

## Overview
Flappy Bird is a simple 2D game built using Java. The objective is to navigate a bird through a series of pipes without colliding with them. The game is inspired by the classic Flappy Bird mobile game.

## Features
- Smooth 2D gameplay
- Realistic gravity and collision detection
- Animated bird movement
- Score tracking system
- Background and pipe graphics

## Project Structure
```
FLAPPYBIRD/
│── bin/                     # Compiled Java class files
│── lib/                     # External libraries (if any)
│── src/                     # Source code and assets
│   │── App.java             # Main application entry point
│   │── FlappyBird.java      # Core game logic
│   │── FlappyBird$Bird.class # Compiled Bird class
│   │── FlappyBird$Pipe.class # Compiled Pipe class
│   │── flappybirdbg.png     # Game background
│   │── bottompipe.png       # Pipe graphic
│   │── toppipe.png          # Pipe graphic (top)
│── README.md                # Project documentation
```

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/prasanthh71/FlappyBird.git
   ```
2. Navigate to the project directory:
   ```sh
   cd FlappyBird
   ```
3. Compile the Java files:
   ```sh
   javac -d bin src/*.java
   ```
4. Run the game:
   ```sh
   java -cp bin App
   ```

## Dependencies
- Java Development Kit (JDK 8 or later)
- Any Java-compatible IDE (VS Code, IntelliJ IDEA, Eclipse, etc.)

## How to Play
- Press **Spacebar** to make the bird jump.
- Avoid colliding with the pipes.
- Try to score as high as possible!

## Screenshots
(Include game screenshots here)

## Contributing
Feel free to submit pull requests for improvements, bug fixes, or new features!

## License
This project is licensed under the MIT License.

---

Enjoy playing Flappy Bird! 🚀

