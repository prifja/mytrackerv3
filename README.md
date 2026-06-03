# MyTracker

A personal workout tracking PWA (Progressive Web App) built for mobile. Track your gym sessions, monitor progress, and get AI-powered coaching — all from your iPhone home screen.

---

## Features

- **Push / Pull / Legs split tracking** with session history
- **AI Coach** — analyses your last sessions and gives specific advice before each workout
- **Personalised Plan** — optimised PPL template based on your training history
- **Personal Best** tracking per exercise
- **8-Week Full Body Program** — guided beginner program with checklist and progress bar
- **Rest Timer** — 90s default with quick presets and audio alarm
- **Draft auto-save** — in-progress sessions saved automatically
- **Edit sessions** — go back and fix a logged workout
- **Dark / Light mode** — follows device setting automatically
- **Free Note mode** — log cardio, yoga, walks or anything freely
- **Import logs** — paste raw workout notes and AI parses them into sessions

---

## Tech

- Single HTML file — no framework, no build step
- Vanilla JS + CSS custom properties
- localStorage for data persistence
- Anthropic Claude API for AI coaching and log parsing
- PWA — add to iPhone home screen via Safari → Share → Add to Home Screen

---

## Deploy

Hosted via GitHub Pages. Every commit to `main` auto-deploys.

Live at: [prifja.github.io/mytracker](https://prifja.github.io/mytracker)

---

## Usage

1. Open the link in **Safari** on iPhone
2. Tap **Share → Add to Home Screen**
3. Open from your home screen like a native app

---

## Local dev

No build tools needed. Just open `index.html` in a browser.

```bash
open index.html
```

---

*Built with Claude — iteratively designed and developed through conversation.*
