# 🎮 Connect 4 Game Using Minimax Algorithm (C++)

This is a **DSA-based project** that implements the classic **Connect 4** game using the **Minimax Tree Algorithm with Alpha-Beta Pruning** for the AI decision-making. The game supports both **Player vs AI** and **2 Player** modes.

## 📌 Project Info

- **Course**: Data Structures and Algorithms
- **Topic**: Game Tree and Minimax Algorithm
- **Team Members**:
  - 20BCE189
  - 20BCE195
  - 20BCE211

## 🧠 AI Strategy

The AI uses the **Minimax Algorithm** with **Alpha-Beta Pruning** to efficiently simulate future game states and determine optimal moves.

Heuristics are applied to evaluate non-terminal game states based on:
- Number of possible connect-4 patterns
- Block opponent's winning chances
- Prefer center positions

## 🧾 Features

- 🎮 Player vs Player Mode
- 🤖 Player vs AI Mode (3 Difficulty Levels)
- 🧠 AI controlled by Minimax + Alpha-Beta pruning
- 🔍 Visual Board Display in Terminal
- ⏱️ Turn Tracking and Win Detection
- 💻 Clean Terminal UI with color support

---

## 📷 Demo

```bash
-0-1-2-3-4-5-6-
| | | | | | | |
| | | | | | | |
| | | | | | | |
| | | | | | | |
| | | |O| | | |
| | |X|O| | | |
---------------
