# 🪨 Nimm Game: Human vs AI

Nimm is an ancient strategy game where players take turns removing stones from a pile. The goal is **not to take the last stone** — the player who does **loses**.

This Python implementation supports:
- 🔢 **1, 2, or 3 stones** per turn
- 🤖 **Computer opponent** (random or smart AI)
- 🧠 Smart AI uses winning strategy based on modular arithmetic
- ♻️ **Divisible-by-3 = extra turn** rule
- 👤 Human vs Computer gameplay

---

## 🎮 How to Play

1. Game starts with **20 stones**.
2. Players alternate turns, removing **1, 2, or 3 stones**.
3. If the **number of stones left after your turn is divisible by 3**, you get an **extra turn**.
4. **The player who takes the last stone loses**.
5. You can choose:
   - If you want to be **Player 1 or 2**
   - Whether the computer plays **smart or random**

---

## 🧠 AI Strategy

- **Random AI**: Picks randomly between 1, 2, or 3 stones.
- **Smart AI**: Tries to leave a multiple of 4 stones after its move (optimal strategy in 1–3 stone version of Nimm).

---

## 🧪 Example Gameplay
Do you want to be Player 1 or 2? (Enter 1 or 2): 1
Should the computer play smart? (y/n): y

There are 20 stones left.
Player 1 (You):
Would you like to remove 1, 2, or 3 stones? 3

There are 17 stones left.
Player 2 (Computer):
Computer removes 1 stone(s).

There are 16 stones left.
Player 1 (You):
...
### Requirements
- Python 3.x
