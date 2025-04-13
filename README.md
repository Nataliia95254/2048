# 🎮 2048 Game – JavaScript Puzzle

A complete implementation of the classic  2048 game built with vanilla JavaScript, HTML, and CSS. Slide tiles to combine them and try to create the 2048 tile!

## 🚀 Live demo

Experience the live website: [2048 game](https://nataliia95254.github.io/2048/)

## 🛠️ Features

- ✅ 4×4 grid with dynamic tile movement
- ✅ Fully functional game logic written in JavaScript
- ✅ Keyboard controls using arrow keys
- ✅ Merging and movement logic with proper rules
- ✅ Random tile generation (90% 2s, 10% 4s)
- ✅ Score tracking and game status (playing, won, lost)
- ✅ Responsive UI with restart functionality
- ✅ Game starts with the "Start" button, switches to "Restart" after the first move
- ✅ Win and game over conditions with messages



## 🧠 Game Rules

- Merge tiles with the same number by moving them in any direction.
- After every move, a new tile (2 or 4) spawns in a random empty spot.
- Two tiles merge into one with double the value.
- Tiles can merge only once per move.
- You win when you reach **2048**.
- You lose when no moves are left.



## 🛠️ Technologies Used

- Vanilla **JavaScript**
- **HTML5**
- **CSS3**

---

## 🧩 Game Class API

Implemented in `src/modules/Game.class.js`

### Public Methods:

- `constructor(initialState?)`: Initializes the board with optional initial state.
- `getState()`: Returns the current game board (4×4 array).
- `getScore()`: Returns the current score.
- `getStatus()`: Returns `'playing'`, `'won'`, or `'lost'`.
- `moveLeft()`, `moveRight()`, `moveUp()`, `moveDown()`: Move logic in all directions.
- `start()`: Starts a new game.
- `restart()`: Resets the game to initial state.


## 🎮 How to Play

- **Start the Game**: Click the "Start" button.
- **Use Arrow Keys**: Slide tiles in any direction.
- **Watch the Board**: Combine tiles, increase your score, and aim for 2048!
- **Restart**: Click "Restart" anytime to try again.



## 🚀 Getting Started

Follow these steps to run the project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/Nataliia95254/2048
   cd mybike

2. **Install dependencies**
    ```bash
    npm install
    # or
    yarn install
3. **Run the project locally**
    ```bash
    npm start
    # or
    yarn start
