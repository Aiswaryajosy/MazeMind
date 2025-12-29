# MazeMind 2D - Ultimate Edition

**MazeMind 2D** is an advanced browser-based maze game featuring a "Dungeon Master" AI that adapts to your skill level in real-time.

## 🎮 Play the Game
[Click here to play the game!](https://aiswaryajosy.github.io/MazeMind/)

## 🧠 AI & Features

### The Dungeon Master (Q-Learning)
The game utilizes a **Q-Learning Reinforcement Learning** model acting as a "Dungeon Master." 
- It observes your performance (Time, Moves, Collisions, Trap Falls).
- It classifies your state as **Fast** (Too Easy), **Medium**, or **Slow** (Too Hard).
- It dynamically adjusts the difficulty (Maze density, Trap count) to keep the game engaging.

### The Explorer Agent
You can watch an **AI Explorer** solve the maze!
- It uses a custom memory grid to map the environment.
- It prioritizes exploring unknown areas and remembers Trap locations.
- It uses **A* Pathfinding** to navigate to the exit once discovered.

### Dynamic Shifting
- If enabled, the maze walls shift and change while you are playing.
- The game uses a "Bridge Builder" algorithm to ensure the maze remains solvable even after walls move.

## 🕹️ Controls
- **Arrow Keys:** Move the Robot.
- **ESC:** Pause Game.
- **Menu:** Change Game Mode (Human, A* Solver, AI Explorer).

## 🛠️ Tech Stack
- HTML5 Canvas (Rendering)
- Vanilla JavaScript (Game Logic)
- TailwindCSS (UI Styling)
- GSAP (Animations)

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
