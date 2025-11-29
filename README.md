# 🚀 Galaxy Wars

A 2D space survival game built with **C++** and **SFML**, demonstrating advanced Object-Oriented Programming concepts.

## 📝 About

Galaxy Wars is a space shooter where you pilot a spaceship, battle enemies, dodge asteroids, and collect power-ups to survive increasingly difficult waves. This project was developed as part of an Object-Oriented Programming course to demonstrate mastery of OOP principles without relying on STL containers.

## ✨ Features

- **Dynamic Gameplay**: Face waves of enemies with varying difficulty levels
- **Multiple Enemy Types**: Basic, Fast, and Tank enemies with unique behaviors
- **Power-Up System**: Collect shields, health boosts, score multipliers, and fire rate upgrades
- **Collision Detection**: Real-time collision system for projectiles, enemies, and asteroids
- **Score Tracking**: High score system with persistent file storage
- **Custom Data Structures**: Implements `DynamicArray<T>` template class (no STL containers)

## 🎮 Controls

- **Arrow Keys / WASD** - Move spaceship
- **Space** - Shoot projectiles
- **Escape** - Pause game
- **Enter** - Start game (from menu)
- **R** - Restart (from game over)

## 🏗️ Architecture

Built with **13 classes** demonstrating:
- Inheritance hierarchies (Single & Multilevel)
- Polymorphism & Dynamic Binding
- Abstract classes & Pure Virtual Functions
- Template Programming
- Exception Handling
- File I/O (Text & Binary)
- Operator Overloading
- Copy Constructors & Deep Copy
- Custom Memory Management

**Note**: Project follows strict guidelines - **no STL containers** (vector, list, map, etc.) are used. All dynamic collections utilize a custom `DynamicArray<T>` template class.

## 🛠️ Tech Stack

- **Language**: C++17
- **Graphics**: SFML (Simple and Fast Multimedia Library)
- **Build System**: Make
- **Allowed Libraries**: `<string>`, `<fstream>`, `<cmath>`, `<ctime>`, `<cstdlib>`

## 📋 Requirements

- C++ compiler (g++ recommended)
- SFML 2.5+
- Make (for building)
- Font file (e.g., arial.ttf)

## 🚀 Quick Start

```bash
# Install SFML
sudo apt-get install libsfml-dev  # Ubuntu/Debian
brew install sfml                  # macOS

# Clone repository
git clone https://github.com/yourusername/galaxy-wars.git
cd galaxy-wars

# Compile
make

# Run
./GalaxyWars
```

## 🎓 Academic Project

This project was created for **Object-Oriented Programming (Fall 2025)** at National University of Computer & Emerging Sciences, Islamabad Campus. It demonstrates comprehensive understanding of OOP principles through practical game development.

**Key Constraint**: No STL containers allowed - all data structures implemented from scratch.

## 📄 License

This project is for educational purposes.

---

*Developed with 🎮 and OOP principles*
