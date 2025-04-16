# 🎮 Connect 4 Game Using Minimax Algorithm (C++)

This is a **DSA-based project** that implements the classic **Connect 4** game using the **Minimax Tree Algorithm with Alpha-Beta Pruning** for the AI decision-making. The game supports both **Player vs AI** and **2 Player** modes.

---

## 📌 Project Info

- **Course**: Data Structures and Algorithms  
- **Topic**: Game Tree and Minimax Algorithm  
- **Team Members**:  
  - 202404055  
  - 202404019 
  - 202401491
  - 202401495 

---

## 🧠 AI Strategy

The AI uses the **Minimax Algorithm** with **Alpha-Beta Pruning** to efficiently simulate future game states and determine optimal moves.

**Heuristics applied:**
- Count of potential winning combinations
- Blocking opponent’s chances
- Prefer center columns (for more branching paths)

---

## 🧾 Features

- 🎮 Player vs Player Mode  
- 🤖 Player vs AI Mode (3 Difficulty Levels)  
- 🧠 AI powered by Minimax + Alpha-Beta pruning  
- 🔍 Visual Board Display in Terminal  
- ⏱️ Turn Tracking and Win Detection  
- 💻 Terminal UI with basic colors  

---

## 📷 Demo

```
-0-1-2-3-4-5-6-
| | | | | | | |
| | | | | | | |
| | | | | | | |
| | | | | | | |
| | | |O| | | |
| | |X|O| | | |
---------------
```

- `O` = Player  
- `X` = AI  

---

## 🛠️ Installation & Run

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/connect4-minimax.git
cd connect4-minimax
```

### 2. Compile the Code
```bash
g++ -o connect4 connect4.cpp
```

### 3. Run the Game
```bash
./connect4
```

---

## 🕹️ How to Play

### 🎮 Game Modes:
- **Player vs AI**
  - Choose difficulty:
    - Easy (Depth 1)
    - Medium (Depth 3)
    - Hard (Depth 5)
- **2 Player Mode**
  - Take turns dropping pieces

### 🧾 Controls:
- Enter a column number (0–6) when prompted
- The board updates after every move
- Game ends on win or draw

---

## 🔎 Code Structure

| Function        | Description                          |
|----------------|--------------------------------------|
| `playGame()`    | Main game loop                      |
| `userMove()`    | Handles player input                |
| `aiMove()`      | AI decision using Minimax           |
| `miniMax()`     | Recursive evaluation                |
| `makeMove()`    | Drops a piece in the board          |
| `winningMove()` | Detects win condition               |
| `tabScore()`    | Board evaluation heuristic          |
| `printBoard()`  | Colored board display               |
| `setDifficulty()` | AI difficulty selection           |
| `initBoard()`   | Initializes/reset board             |

---

## ⚙️ Algorithm Details

### ✅ Minimax Algorithm:
- Evaluates all possible outcomes to a certain depth
- Chooses the move maximizing AI’s minimum guaranteed outcome

### 🧠 Alpha-Beta Pruning:
- Skips unpromising branches
- Improves efficiency drastically by reducing computation

---

## 📚 Dependencies

- Standard C++ Libraries  
- ANSI escape codes for colored terminal output  
  (works best on Linux/macOS terminals)

---

## ✅ To Do / Improvements

- [ ] GUI version using SFML / SDL  
- [ ] Web version using JavaScript  
- [ ] Networked Multiplayer  
- [ ] Enhanced heuristics (advanced pattern detection)  

---

## 📄 License

This project is developed as part of a university assignment and is open for educational and non-commercial use.

---

## 🙌 Acknowledgements

Thanks to our DSA faculty and guides for support and insight into game theory, recursion, and algorithm design.
