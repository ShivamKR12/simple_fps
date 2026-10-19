# Panda3D WebGL Simple FPS Demo

A browser-based 3D First-Person Shooter demo built with the [Panda3D](https://www.panda3d.org/) game engine and compiled to WebGL / WebAssembly using Emscripten.

## 🎮 Live Demo

Play directly in your browser:
**https://shivamkr12.github.io/simple_fps/**

## 🕹️ Controls

- **WASD / Arrow Keys**: Move player
- **Mouse**: Look around / Aim
- **Left Mouse Click**: Shoot / Action
- **Space**: Jump

## 🚀 Running Locally

Because WebAssembly and WebGL require cross-origin isolation and local HTTP serving, start a simple local server:

Using Python:
```bash
python -m http.server 8000
```

Then open `http://localhost:8000` in any modern web browser.

## 🛠️ Tech Stack

- **Game Engine**: Panda3D
- **Runtime**: WebGL / WebAssembly (Emscripten)
- **Deployment**: GitHub Pages
