# Pixel Office 🏢

A fun 2D pixel art "AI Office" web application — The Sims meets an AI agent dashboard.

![Pixel Office](https://img.shields.io/badge/Pixel-Office-purple?style=for-the-badge)

## Features

- 🎮 Side-view pixel art office with procedurally drawn characters
- 🤖 5 pre-built AI agents with unique appearances and roles
- 🏃 Smooth walking animations, sitting, typing, and idle behaviors
- ☕ Coffee machine with steam animation, water cooler, couch, plants
- 🌅 Day/night cycle based on real time
- 🖱️ Click agents to view details, assign tasks, send messages
- 📢 Broadcast messages to all agents
- 🎲 Random office events (jokes, eureka moments, etc.)
- ➕ Add custom agents with color picker
- 📊 Activity logs per agent

## Tech Stack

- Single HTML file — no dependencies
- Canvas-based pixel art rendering
- Pure vanilla JavaScript
- Responsive design

## Run Locally

Just open `index.html` in a browser!

## Docker

```bash
docker build -t pixel-office .
docker run -p 8080:80 pixel-office
```

Then visit http://localhost:8080

## License

MIT
