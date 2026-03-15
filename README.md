# DiskGuard — 3D Bounce

A classic 3D Breakout / Bounce game built with [Three.js](https://threejs.org/). Destroy all the bricks by bouncing the ball off your paddle!

## 🎮 Play Now

**[▶ Play 3D Bounce](https://charleshepos-png.github.io/DiskGuard/)**

## How to Play

1. Open the link above — or open `index.html` locally with a web server.
2. Click **Play** to start the game.
3. Move your **mouse** (or finger on mobile) to control the paddle.
4. **Click** (or tap) to launch the ball.
5. Bounce the ball to break all the bricks and advance to the next level.

## Game Features

- **3D arena** with dynamic lighting, shadows, and particle effects
- **Multiple levels** — clear all bricks to advance; speed increases each level
- **Durable bricks** — the top rows take two hits to destroy
- **Score system** — higher rows earn more points
- **Lives** — you start with 3 lives; lose one if the ball passes the paddle
- **Touch support** — playable on mobile devices
- **No build step** — just open the HTML file and play

## Controls

| Input | Action |
|-------|--------|
| Mouse move / Touch drag | Move paddle left & right |
| Click / Tap | Launch ball |

## Tech Stack

- **Three.js** (v0.160) — loaded from CDN, no install required
- Pure HTML + JavaScript — single self-contained file

## Deployment

This game is automatically deployed to **GitHub Pages** on every push to `main`.

To enable GitHub Pages for the first time:
1. Go to your repository **Settings** → **Pages**
2. Under **Build and deployment**, set Source to **GitHub Actions**
3. The included workflow (`.github/workflows/deploy.yml`) handles the rest

To run locally:
```bash
# Any simple HTTP server works — ES modules require a server
npx serve .
# or
python3 -m http.server 8080
```
Then open `http://localhost:8080` in your browser.