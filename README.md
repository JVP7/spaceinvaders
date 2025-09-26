# Space Invaders (Pygame)

A classic **Space Invaders** clone written in Python with **Pygame**.  
Blast waves of aliens, dodge lasers, and chase the elusive mystery ship.  
Press **Space** to fire; when the game ends, press **Space** again to restart.

---

## 🎮 Gameplay & Controls
- **Left / Right Arrow** — Move the spaceship  
- **Space** — Fire laser  
- **Space (on GAME OVER / YOU WIN)** — Restart the game  
- **Esc / Cmd+Q** — Quit window

---

## ✨ Features
- Alien formations with increasing difficulty  
- Player spaceship with laser projectiles  
- Obstacles/shields that degrade with hits  
- Mystery ship that occasionally flies across the top  
- Score tracking (see `highscore.text`)  
- Win/lose detection and restart flow  

---

## 🗂️ Project Structure

├── main.py          # Entry point: sets up the game and loop  
├── game.py          # Game orchestration, groups, collisions, state  
├── alien.py         # Alien sprite & behavior  
├── spaceship.py     # Player sprite & controls  
├── laser.py         # Laser projectile  
├── obstacle.py      # Obstacles (shields)  
├── highscore.text   # Stores high score  
├── graphics/        # Sprites/images  
├── sounds/          # Sound effects / music  
└── font/            # Game font(s)  

---

## ⚙️ Requirements
- **Python 3.10+** (macOS/Linux/Windows)  
- **Pygame**

Install Pygame globally:
\`\`\`bash
python3 -m pip install --upgrade pip
python3 -m pip install pygame
\`\`\`

---

## ▶️ How to Run
From the project root:
\`\`\`bash
python3 main.py
\`\`\`

---

## 🔊 Assets
- Images → `graphics/`  
- Audio → `sounds/`  
- Fonts → `font/`  

All paths are already set up to load from these folders.

---

## 🧪 Troubleshooting
- **Window doesn’t open on macOS:** use `python3`, not `python`.  
- **No audio:** check system sound permissions.  
- **Mystery ship spawns too often:** tweak spawn logic in `game.py`.  
- **ModuleNotFoundError: pygame:** reinstall with `python3 -m pip install pygame`.  

---

## 📝 Roadmap / TODO
- Fix the highscore saving
- Fix the Win menu

---

## 📄 License
This project is released under the **MIT License**. See `LICENSE` for details.
