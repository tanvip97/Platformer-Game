# 🕹️ Python Platformer Game

A 2D platformer game built using **Python** and **Pygame**, featuring shooting mechanics, enemies (bees and worms), custom animations, and tile-based level design using **Tiled Map Editor**.

## 🚀 Features

- 👨‍💻 Player character with movement and shooting
- 🐝 Bee and worm enemies with basic AI
- 💥 Bullet collisions with enemies
- 🧱 Multi-layered map design using **Tiled**
- 🎨 Animated sprites for dynamic visuals
- ⏱️ Custom timers for game logic
- 📦 Organized sprite and tile assets

## 🖥️ Gameplay Preview

_Add a GIF or screenshot of your game here_

## 🛠️ Tech Stack

- **Language**: Python  
- **Library**: Pygame  
- **Level Design**: Tiled Map Editor (`.tmx` files)  
- **Assets**: Custom and/or free game assets

## 📁 Folder Structure

```
├── assets/
│   ├── player/
│   ├── enemies/
│   └── tiles/
├── maps/
│   └── level1.tmx
├── main.py
├── settings.py
└── README.md
```

## ▶️ How to Run

1. Make sure you have **Python 3.x** installed.
2. Install **Pygame**:

```bash
pip install pygame
```

3. Run the game:

```bash
python main.py
```

## 🎮 Controls

| Key        | Action           |
|------------|------------------|
| Arrow keys | Move left/right  |
| Spacebar   | Jump             |
| `Z`        | Shoot bullets    |

## 🧱 Tiled Map Editor

If you want to edit or create new levels:

1. Download [Tiled](https://www.mapeditor.org/).
2. Open `.tmx` files in the `maps/` directory.
3. Design your level and save it — the game will load the updated map!

## 🧩 Known Issues / To-Do

- [ ] Add background music and sound effects  
- [ ] Add health/lives system  
- [ ] Add UI for score and lives  
- [ ] Implement multiple levels  

## 🤝 Contributing

Feel free to fork this repo, improve the game, and make a pull request!

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
