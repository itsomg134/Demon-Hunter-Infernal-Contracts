# Demon Hunter: Infernal Contracts

![Demon Hunter Banner](https://img.shields.io/badge/Demon_Hunter-Infernal_Contracts-red)
![License](https://img.shields.io/badge/License-MIT-blue)
![Unity](https://img.shields.io/badge/Engine-Unity-000000)
![Platforms](https://img.shields.io/badge/Platforms-PC%2C%20PS5%2C%20Xbox-green)

> **A Gothic action RPG where every demon is a choice: Purge them for power or bind them for knowledge.**

## 📖 Overview

**Demon Hunter: Infernal Contracts** is a procedurally generated horror-action RPG where you track, fight, and capture supernatural entities across multiple realms. Every encounter presents a strategic choice: execute demons for immediate rewards or risk capturing them for long-term power and secrets.

<img width="1869" height="1992" alt="image" src="https://github.com/user-attachments/assets/45f5ca4d-eade-4683-b0d0-c40648d11259" />

## ✨ Features

### 🔥 Dynamic Combat System
- **Real-time combat** with precise dodging, parrying, and combo mechanics
- **Elemental affinity system** - exploit demon weaknesses (Fire/Ice/Shadow/Divine)
- **Sanity mechanics** - prolonged exposure to demons causes hallucinations and debuffs

### ⚔️ Kill or Capture System
```
┌─────────────────┬─────────────────────────────┐
│     KILL        │          CAPTURE           │
├─────────────────┼─────────────────────────────┤
│ • Instant gold  │ • Add to Demon Codex       │
│ • Crafting mats │ • Extract unique abilities │
│ • Purist rep    │ • Summon as battle allies  │
│ • No risk       │ • Research for bonuses     │
└─────────────────┴─────────────────────────────┘
```

### 📚 Demon Codex & Progression
- Capture demons to unlock **lore entries** and **passive bonuses**
- **Three skill trees**: Hunter (kill-focused), Occultist (capture-focused), Survivor (defensive)
- **Demon fusion system** - combine captured entities to create new variants
- **Safehouse management** - upgrade your base, prison cells, and research facilities

### 🌍 Procedural World
- **Four distinct realms**: Mortal, Shadow Veil, Abyssal Layers, Purgatory
- **Dynamic contracts** - randomly generated missions with unique objectives
- **Living world** - your choices affect faction relationships and world events

## 🎮 Gameplay Preview

```python
# Simplified combat logic example
def engage_demon(hunter, demon):
    while demon.is_alive() and hunter.is_alive():
        # Combat phase
        hunter.attack(demon)
        demon.retaliate(hunter)
        
        # Decision point
        if demon.health < 20 and hunter.has_binding_circle():
            choice = player_decision("Kill or Capture?")
            if choice == "Capture":
                success = hunter.attempt_capture(demon)
                if success:
                    hunter.codex.add(demon)
                    return "Captured"
        # Default to kill
        hunter.execute(demon)
        return "Killed"
```

## 🛠️ Installation

### Requirements
- **Unity 2022.3+**
- **Windows 10/11** or **Linux** (Ubuntu 20.04+ recommended)
- **8GB RAM** minimum, 16GB recommended
- **DirectX 12** compatible GPU

### Quick Start
```bash
# Clone the repository
git clone https://github.com/yourusername/demon-hunter.git
cd demon-hunter

# Open in Unity
# Or run the compiled version (when available)
./DemonHunter.exe
```

## 📁 Project Structure

```
demon-hunter/
├── Assets/
│   ├── Scripts/
│   │   ├── Core/          # Game manager, save system
│   │   ├── Combat/        # Combat mechanics, abilities
│   │   ├── Demons/        # Demon AI, behaviors, types
│   │   ├── UI/           # Interface elements
│   │   └── World/        # Realm generation, NPCs
│   ├── Prefabs/          # Game objects
│   ├── Scenes/           # Game scenes
│   └── Resources/        # Game assets
├── Docs/                 # Design documents, lore
├── Builds/              # Compiled versions
└── Tests/               # Unit tests
```

## 🧪 Development Status

| Feature | Status | Version |
|---------|--------|---------|
| Core Combat System | ✅ Complete | v1.0 |
| Demon AI & Behaviors | ✅ Complete | v1.0 |
| Kill/Capture Mechanics | ✅ Complete | v1.0 |
| Procedural Contracts | 🟡 In Progress | v1.1 |
| Multiplayer Co-op | 🟡 Planned | v1.3 |
| Demon Fusion System | 🔴 Planned | v1.2 |

## 👥 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Areas Needing Contribution:
- Additional demon types and behaviors
- New realm generation algorithms
- UI/UX improvements
- Performance optimization
- Localization support

## 📝 Code of Conduct

Please read our [Code of Conduct](CODE_OF_CONDUCT.md) before participating. We're committed to providing a welcoming environment for all contributors.

## 🐛 Bug Reports & Feature Requests

Found a bug or have an idea? [Open an Issue](https://github.com/yourusername/demon-hunter/issues)!

Please include:
- Game version
- Steps to reproduce
- Expected vs actual behavior
- Screenshots/videos if possible

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by classic horror games and monster hunting series
- Special thanks to our early testers and contributors
- Shader magic by [Custom Shaders Pack](link)
- Sound design by [Audio Assets](link)

## 📞 Contact

Om Gedam

GitHub: @itsomg134

Email: omgedam123098@gmail.com

Twitter (X): @omgedam

LinkedIn: Om Gedam

Portfolio: https://ogworks.lovable.app
