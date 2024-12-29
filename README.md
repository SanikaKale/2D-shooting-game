# 2D-shooting-game
Unity based shooting game
here's the game:
https://sanikakale.itch.io/2d-shooter

## Overview
This project is a 2D interactive shooting game developed in Unity using C#. Players control a character to navigate through levels, shoot enemies, and score points while avoiding obstacles and hazards.

---

## Features
- **Player Controls:** Smooth movement and shooting mechanics.
- **Enemy AI:** Dynamic enemy behavior with increasing difficulty.
- **Weapons System:** Multiple weapon types with different effects.
- **Scoring System:** Tracks player score and displays a leaderboard.
- **Power-Ups:** Collectible items for health, ammo, and special abilities.
- **Visual Effects:** Particle effects for shooting, explosions, and more.
- **Sound Effects:** Engaging background music and interactive sound effects.

---

## Prerequisites
- Unity 2021.3.x or later.
- Basic knowledge of Unity and C#.

---

## Getting Started

### 1. Clone the Repository
```bash
git clone <repository-url>
```

### 2. Open the Project in Unity
1. Launch Unity Hub.
2. Click on **Open Project** and navigate to the cloned folder.

### 3. Play the Game
- Press the **Play** button in Unity to start the game.

---

## Controls
- **W/A/S/D or Arrow Keys:** Move the player.
- **Left Mouse Button:** Shoot.
- **Spacebar:** Activate special ability (when available).
- **P:** Pause/Resume the game.

---

## Project Structure
```
Assets/
├── Scripts/
│   ├── Player/
│   │   ├── PlayerMovement.cs
│   │   ├── PlayerShooting.cs
│   ├── Enemies/
│   │   ├── EnemyAI.cs
│   │   ├── EnemySpawner.cs
│   ├── PowerUps/
│   │   ├── PowerUpController.cs
│   ├── UI/
│       ├── ScoreManager.cs
│       ├── PauseMenu.cs
├── Prefabs/
│   ├── Player.prefab
│   ├── Enemy.prefab
│   ├── PowerUp.prefab
├── Scenes/
│   ├── MainMenu.unity
│   ├── Level1.unity
│   ├── GameOver.unity
├── Audio/
│   ├── BackgroundMusic.mp3
│   ├── ShootingSound.wav
```

---

## Gameplay Mechanics

### 1. Player
- Moves using keyboard inputs.
- Shoots projectiles to eliminate enemies.
- Collects power-ups to boost health, ammo, or abilities.

### 2. Enemies
- Spawn dynamically based on player progress.
- Varying difficulty with unique attack patterns.

### 3. Power-Ups
- Spawn at random locations.
- Types include:
  - Health Boost
  - Ammo Refill
  - Shield Activation

### 4. Scoring
- Gain points for defeating enemies.
- Lose points for taking damage.
- Final score displayed at the end of the game.

---

## Customization
- Modify difficulty by adjusting parameters in the `EnemySpawner.cs` script.
- Add new levels by creating scenes and linking them to the main menu.
- Customize UI elements using Unity's Canvas system.

---

## Contribution
Contributions are welcome! Follow these steps:
1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/YourFeature`.
3. Commit your changes: `git commit -m 'Add YourFeature'`.
4. Push to the branch: `git push origin feature/YourFeature`.
5. Submit a pull request.

---
