# Foundry

A single-file learning app for becoming a full-stack maker — **websites, games, and mobile** — in a fixed order.

Open `index.html` in any modern browser, or serve the folder so you can install it as an app.

```bash
cd foundry
python3 -m http.server 8080
```

Then visit `http://localhost:8080`. On your phone (same Wi‑Fi), use your computer’s local IP.

## Why this exists

You already opened too many tools: Figma, Canva, Affinity, DaVinci, Godot, Python, C#, HTML, CSS, JS, TypeScript, React. The hard part is not finding tutorials. It is knowing **what to do next**.

Foundry’s Home screen always offers **one** next lesson on a spine:

1. Programming ideas (shown in JS, Python, GDScript, and C# side by side)
2. HTML → CSS → JavaScript in the browser
3. Design systems you can actually implement
4. TypeScript + React
5. Python backend
6. Mobile as a PWA, then React Native
7. Godot (GDScript first; C# after you ship one small game)

## What’s inside

- **Path** — the full spine, with progress
- **Lessons** — short reads, quizzes, flashcards
- **Reviews** — spaced repetition (SM-2 style)
- **Playground** — HTML/CSS/JS (always) and Python via Pyodide (needs network once)
- **Rosetta** — the same idea in four languages
- **Projects** — portfolio work with milestone checklists

Progress is stored in **this browser** (`localStorage`). Export a backup from Profile if you switch devices.

## Install (PWA)

- **Android Chrome / desktop Chrome or Edge:** menu → Install app / Add to Home screen  
- **iPhone:** Safari → Share → Add to Home Screen  

Serve over `http://` or `https://` (opening the file directly works for learning, but install/offline needs a local server).
