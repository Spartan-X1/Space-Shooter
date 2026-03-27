# 🚀 Space Shooter: Advanced Wave-Based Combat System

A sophisticated 2D space shooter game featuring advanced enemy AI, dynamic weapon systems, and progressive wave-based gameplay. Built with Python and Raylib for high-performance graphics and audio.

## 🎮 Game Features

### Core Gameplay
- **Dynamic Wave System**: Progressive difficulty with 5+ distinct enemy types
- **Advanced Combat**: Multiple weapon types with unique firing patterns
- **Smart Enemy AI**: Sophisticated movement patterns and targeting systems
- **Health & Damage**: Invulnerability frames and visual feedback systems
- **High-Performance Graphics**: Smooth 60 FPS gameplay with particle effects

### Enemy Types & AI Behaviors
- **🛡️ Tank Enemies**: Heavy armor, slow movement, devastating cannon attacks
- **⚡ Swarm Enemies**: Fast, erratic movement with rapid-fire weapons
- **🎯 Sniper Enemies**: Long-range precision attacks with charging mechanics
- **💥 Bomber Enemies**: Area-effect spread shot patterns
- **🤖 Standard Enemies**: Balanced units with adaptive movement patterns

### Weapon Systems
- **Standard Laser**: Reliable single-shot projectiles
- **Triple Shot**: Spread-pattern firing for area coverage
- **Rapid Fire**: High rate-of-fire for sustained damage
- **Enemy Weapons**: Specialized armaments per enemy type

### Technical Highlights
- **Collision Detection**: Optimized circle-rectangle collision systems
- **Audio Engine**: Raylib library
- **Animation System**: Smooth sprite animations and explosion effects
- **Performance Optimization**: Efficient sprite culling and memory management

## 🛠️ Technology Stack

- **Language**: Python 3.8+
- **Graphics**: Raylib (via PyRay bindings)
- **Audio**: Raylib Audio System
- **Architecture**: Object-Oriented Design with Component Pattern
- **Performance**: 60 FPS target with optimized rendering pipeline

## 🚀 Installation & Setup

### Prerequisites
```bash
pip install pyray
pip install cffi  # Required for Raylib bindings
```

### Clone and Run
```bash
git clone https://github.com/yourusername/space-shooter.git
cd space-shooter
python main.py
```

### Project Structure
```
code/
├── main.py              # Main game loop and core systems
├── sprites.py           # Sprite classes and collision systems
├── weapons.py           # Weapon implementations and combat mechanics
├── waves.py             # Wave management and enemy factory
├── settings.py          # Game configuration and constants
├── custom_timer.py      # Timer utility for game events
├── images/              # Sprite textures and visual assets
│   ├── Enemies/         # Enemy sprite variations
│   ├── Lasers/          # Projectile textures
│   └── explosion/       # Animation frames
├── audio/               # Sound effects and music
└── font/                # Game typography
```

## 🎯 Controls

| Key | Action |
|-----|--------|
| `↑↓←→` | Move spaceship |
| `A/D` | Rotate spaceship |
| `Space` | Fire weapon |
| `1/2/3` | Switch weapons |
| `Enter` | Restart (Game Over screen) |
| `F1` | Debug: Show enemy information |

## 🎨 Screenshots & GIF

![image](https://github.com/user-attachments/assets/049cabb0-28f6-49ee-ac95-240c352115b3)
Playing the game (Wave 3) :

![gif](https://github.com/Spartan-X1/Space-Shooter/blob/main/images/Space_Shooter.gif)


## 🏗️ Architecture Overview

### Core Systems
- **Game Loop**: Killing enemies in the current wave & surviving
- **Entity Management**: Efficient sprite pooling and lifecycle management
- **Physics**: Custom collision detection with spatial optimization
- **Audio**: Audio & Music dynamic play for each senario

### Advanced Features
- **Wave Progression**: Fixed progress mechanism for each wave.
- **Enemy AI**: Smart constraint-based AI that combines movement patterns, boundary management, and player tracking to create emergent tactical behaviors
- **Weapon Balance**: Carefully tuned damage, rate of fire, and cooldown systems
- **Visual Effects**: Particle systems for explosions and projectile trails

## 🔧 Configuration

Key gameplay parameters can be adjusted in `settings.py`:

```python
WINDOW_WIDTH, WINDOW_HEIGHT = 1800, 980  # Display resolution
ENEMY_SPEED = 150                        # Base enemy movement speed
PLAYER_SPEED = 500                       # Player movement speed
LASER_SPEED = 600                        # Projectile velocity
ENEMY_SPAWN_INTERVAL = 3                 # Wave timing control
```

## 🗺️ Roadmap(Future)

- [ ] **Boss Battles**: Epic encounters with unique mechanics
- [ ] **Power-Up System**: Temporary abilities and upgrades
- [ ] **Leaderboards**: Global score tracking
- [ ] **Modding Support**: Custom enemy and weapon creation
- [ ] **Mobile Port**: Touch-optimized controls
- [ ] **Shader Effects**: Advanced visual rendering
- [ ] **Networking**: Multiplayer cooperative mode


## 🙏 Acknowledgments

- **Raylib Community**: For the excellent graphics library
- **Python Community**: For the robust ecosystem
- **Game Development Resources**: Inspiration from classic arcade shooters

---

*Built with ❤️ by [Nimish & Anshika] - A showcase of advanced Python game development techniques*
