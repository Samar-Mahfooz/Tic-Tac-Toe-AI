# 🧠 Tic Tac Toe AI (Unbeatable with Minimax + Alpha-Beta Pruning)

This is a command-line Tic Tac Toe game built in Python with an **unbeatable AI opponent**.  
The AI uses the classic **Minimax algorithm**, enhanced with **Alpha-Beta Pruning** and **depth-aware evaluation**, making it play optimally every time.

---

## 🎯 Features

- ✅ Human vs AI (you play as `'o'`, AI is `'x'`)
- ✅ Minimax algorithm for perfect decision-making
- ✅ Alpha-Beta pruning for efficient search
- ✅ Depth-based scoring to prefer faster wins / delayed losses
- ✅ Modular and clean object-oriented Python code
- ✅ Terminal-based, no external dependencies

---

## 🧠 AI Strategy

The AI explores all possible game states using **Minimax**, optimized with:

- **Alpha-Beta Pruning**: cuts unnecessary branches, improving performance
- **Depth-Aware Heuristic**: scores moves based on how quickly a win/loss happens:
  - `score = 10 - depth` for AI wins (prefers quicker wins)
  - `score = -10 + depth` for losses (delays losing)

---

## 🕹️ How to Play

### ▶️ Run the game:

```bash
python tictactoe.py
