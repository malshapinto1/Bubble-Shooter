

# Modern Bubble Shooter 🎯

- **Live Demo**: [Play Now](https://modern-bubble-shooter-game.vercel.app/)

A modern twist on the classic bubble shooter game featuring advanced physics, dynamic visual effects, and strategic gameplay mechanics. Built with pure JavaScript and HTML5 Canvas.

![Gameplay Preview](https://github.com/user-attachments/assets/d8342344-99df-4519-88a0-6d8edc6e0eab)


## Features ✨

- **Hexagonal Grid System** for optimal bubble arrangement
- **Dynamic Match-3 Mechanics** with cluster detection algorithm
- **Modern Visual Effects** including:
  - Glass morphism overlays
  - Dynamic lighting system
  - Particle effect animations
- **Progressive Difficulty** with 10+ levels
- **Physics Simulation** featuring:
  - Elastic collisions
  - Trajectory prediction
  - Bubble snapping mechanics
- **Performance Optimized** for 60 FPS gameplay
- **Responsive Design** that adapts to screen sizes

## How to Play 🕹️

- **Aim**: Move mouse to adjust shooting angle
- **Shoot**: Left click to launch bubbles
- **Match**: Group 3+ same-color bubbles to clear them
- **Score**: Earn bonus points for chain reactions
- **Survive**: Prevent bubbles from reaching the bottom!

**Pro Tip**: Use wall bounces for tricky shots! 🏆

## Technical Highlights 🛠️

### Architecture
- **Dual-Layer Rendering System** (Game Canvas + UI Overlay)
- **MVC Pattern** implementation
- **Object Pooling** for memory optimization

### Algorithms
- **Flood Fill** cluster detection (O(n) complexity)
- **Spatial Partitioning** for collision detection
- **Floating Bubble Detection** using graph traversal

### Performance
- **60 FPS** target frame rate
- **<50MB** memory footprint
- **O(n)** optimized collision checks

## Installation 💻

1. Clone repository:
```bash
git clone https://github.com/your-username/bubble-shooter.git
```

2. Open in browser:
```bash
cd bubble-shooter && open index.html
```

**No dependencies required!** Runs directly in modern browsers.

## Contributing 🤝

Contributions welcome! Please follow these steps:
1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
