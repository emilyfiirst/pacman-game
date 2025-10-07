# 🟡 Pacman in Python

A simple and fun project that recreates the classic **Pac-Man** directly in the **terminal** using **pure Python**.  
The game is based on a text map and uses **ASCII characters** and **text-based sprites** to represent Pac-Man, ghosts, pills, and walls.

---

## 🎮 About the Game

The goal is to **collect all the pills (P)** in the map while **avoiding ghosts (G)**.  
The player controls **Pac-Man (@)**, moving through the maze and trying not to get caught!

---

## 🧱 Game Elements

| Symbol   | Meaning             |
|:--------:|-------------------|
| `@`      | Pac-Man (you)      |
| `G`      | Ghost (enemy)      |
| `P`      | Pill (collectible) |
| `.`      | Empty space        |
| `|` / `-`| Wall               |

---

## ⚙️ Project Structure

```
📁 pacman-terminal
│
├── pacman.py       # Main game logic
├── ui.py           # Text-based visual interface (ASCII)
├── main.py         # Main game loop
├── test_pacman.py  # Unit tests for core functionality
```

---

## 🕹️ How to Play

1. Clone or download the repository:
```bash
git clone https://github.com/emilyfiirst/pacman-terminal.git
```

2. Navigate to the project folder:
```bash
cd pacman-terminal
```

3. Run the game:
```bash
python main.py
```

4. Control Pac-Man using the keyboard keys:
- `w` → move up  
- `s` → move down  
- `a` → move left  
- `d` → move right  

---

## 🧠 Game Mechanics

- Pac-Man moves through the map collecting pills.  
- Ghosts move randomly after each player turn.  
- Hitting a ghost ends the game.  
- Collecting all pills wins the game.  

---

## 👨‍💻 Author

Developed as a **Python learning project** to practice game logic and text-based interfaces.

---
