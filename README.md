# 🏎️ Car Racing Game

A simple 2D car racing game built using **Pygame**. The player controls a car to dodge oncoming traffic while the speed and difficulty increase progressively with each level.

---

## 🎮 Features

- Interactive start menu with buttons
- Game pause/resume functionality
- Countdown before gameplay
- Multiple obstacle car types
- Level system based on dodged cars
- Instruction screen for controls
- Game-over crash animation

---

## 🖥️ Technologies Used

- Python 3
- Pygame Library

---

## 🧠 How It Works

- The game opens with an intro screen offering options to **Start**, **Quit**, or view **Instructions**.
- Once started, the game shows a countdown (`3...2...1...GO!`).
- The player uses:
  - `←` / `→` arrows to move
  - `A` to accelerate
  - `B` to brake
  - `P` to pause
- Cars appear as obstacles that the player must avoid.
- Score increases with each successful dodge.

---

## 🖼️ Screens & Assets

Make sure the following image files are present in the same directory:

```
background.jpg
background2.jpg
car.jpg
car1.jpg
car2.jpg
car4.jpg
car5.jpg
car6.jpg
car7.jpg
download12.jpg
strip.jpg
yellow strip.jpg
```

---

## ▶️ How to Run

### Prerequisites:
- Python 3 installed
- Pygame installed:
  ```bash
  pip install pygame
  ```

### Run the Game:
```bash
python game.py
```

---

## 📁 File Structure

```
.
├── game.py             # Main game logic and UI
├── window.py           # Initial test setup (not required to run)
├── car1.jpg ...        # Car obstacle sprites
├── background.jpg      # Game backgrounds
├── strip.jpg           # Road design
└── yellow strip.jpg    # Lane separator
```

---

## 👩‍💻 Author

**Udita Srivastava**  
GitHub: [udita2404](https://github.com/udita2404)

---
