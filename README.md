# Snake (Vanilla JS + HTML5 Canvas)

A compact, dependency-free Snake game built as a portfolio project to practice: canvas rendering, input handling, state management, and a simple game loop with modern JavaScript features.

## Features

- 30×30 grid on HTML5 Canvas (10px cell size)
- Deterministic tick-based loop with adjustable speed
- Collision detection (walls and self), scoring, difficulty scaling
- Pause/resume functionality for better user experience
- Modern keyboard input handling (uses `key` instead of deprecated `keyCode`)
- Minimal UI with score HUD, restart, and pause controls
- Accessible design with proper ARIA labels and keyboard navigation
- Single-file implementation for easy review and portability

## Controls

- **Arrow Keys** - Turn the snake (Left, Right, Up, Down)
- **Space Bar** - Pause/Resume game
- **R Key** - Restart game at any time
- **Restart Button** - Click to restart
- **Pause Button** - Click to pause/resume

## Run Locally

1. Clone or download the repo
2. Open `index.html` in any modern browser
3. Use arrow keys to move, space to pause, R to restart

## Game Mechanics

- Snake starts with 3 segments moving right
- Eating food increases score and snake length
- Speed increases every 5 points (maximum speed cap at 40ms per tick)
- Game ends when snake hits walls or itself
- Food never spawns on the snake's body

## Tech Stack

- **JavaScript (ES6+)** - Game logic and modern event handling
- **HTML5 Canvas** - 2D rendering and animation
- **CSS3** - Minimal styling with flexbox layout
- **No dependencies** - Pure vanilla implementation

## Code Highlights

- Clean separation of concerns (rendering, game logic, input)
- Comprehensive JSDoc comments for maintainability
- Efficient collision detection and food placement algorithms
- Smooth difficulty progression system
- Accessible UI with proper semantic markup

