# 🎯 Balloon Dodge (Pygame Mini-Arcade)

A fast-paced, minimal Pygame arcade game where you dodge chaotic balloons flying across the screen. Built for fun, polish, and future power-ups.

---

## 🔥 Features

* 🎮 Smooth character movement via keyboard
* 🎈 Randomized balloon generation each frame
* 🖼️ Custom assets (background, character, balloons)
* 🧱 60 FPS rendering with `pygame.time.Clock`
* 📂 Organized `/assets` directory
* 🐳 Dockerized for clean builds & deployment
* ✅ Cross-platform (macOS / Linux / Windows)

> 💡 Future releases will add scoring, sound effects, collision detection, and leaderboards.

---

## 💻 Controls

| Key     | Action            |
| ------- | ----------------- |
| ⬅️ / ➡️ | Move Left / Right |
| ⬆️ / ⬇️ | Move Up / Down    |

---

## 📁 Project Structure

```
.
├── assets/
│   ├── background.jpg
│   ├── bloon.png
│   └── character.png
├── game.py
├── requirements.txt
└── Dockerfile
```

---

## 🚀 Run Locally

```bash
git clone https://github.com/your-username/shooter_game_python.git
cd shooter_game_python
pip install -r requirements.txt
python game.py
```

---

## 🐳 Run with Docker

```bash
docker build -t balloon-dodge .
docker run --rm -it balloon-dodge
```

---

## 🔧 Requirements

* Python 3.11+
* Pygame

```bash
pip install pygame
```

---

## 🧠 Coming Soon - Maybe

* 🔥 AI commentary
* 🏆 Score tracking & leaderboard
* 🎾 Multiplayer 

---

## 👨‍💼 Author

**Mahdi Ashrafee**

---