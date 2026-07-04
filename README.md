# Sattva — Yoga & Ayurveda

A self-contained, single-file Yoga & Ayurveda web app. No build step, no dependencies — pure static HTML with inline CSS + JS.

## What's inside
- `index.html` — the app (served at the site root)
- `yoga.html` — identical copy (so it also works at `/yoga.html`)

## Features
- **Dosha quiz** — maps your Vata / Pitta / Kapha balance
- **My Dosha** — balance meters, rebalancing plan, daily routine (dinacharya)
- **Yoga** — dosha-aligned sequences with a guided practice player (pose timer, progress ring, breath pacer)
- **Ayurveda** — per-dosha foods, herbs, rituals, seasonal tips
- **Breathe** — guided pranayama with a visual pacer
- **Progress** — sessions, minutes, streak, 3-week heatmap (stored in your browser only)
- **Premium** — freemium tiers illustrating monetisation (demo only, no real payments)

## Put it online with GitHub Pages
1. Create a new repository on GitHub and upload these files (Add file → Upload files).
2. Settings → Pages → Source: **Deploy from a branch** → Branch: `main` / `/(root)` → Save.
3. Live at `https://<your-username>.github.io/<repo>/` in about a minute.

## Run locally
```bash
python -m http.server 4173   # then open http://localhost:4173/
```

Wellness & educational content only — not a substitute for professional medical advice.
