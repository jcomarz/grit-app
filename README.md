# GR!T — Intense Fellowship

A personal spiritual operating system built around the GRIT Implementation Plan. One HTML file, zero dependencies, works offline.

## Features

- **Daily Rhythm** — Morning anchor, midday checkpoint, evening debrief with streak tracking
- **Scripture Sandbox** — Personal verse collection with reflections, categories, color coding, Bible API lookup
- **Bible Plans** — 10 pre-built templates + custom plan builder
- **Worship** — Spotify playlist integration with persistent mini-player
- **Brotherhood** — Accountability logging, pillar scoring, manual sharing (local) or live pairing (cloud)
- **Journal** — Tagged daily debriefs searchable by keyword and category
- **Calendar** — Visual overview of your consistency

## How It Works

**Local-first** — Opens instantly, all data stored in your browser. No account needed.

**Optional cloud sync** — One person hosts a Room (free Supabase project), shares a room code. Everyone else just enters the code to join and create their account. Enables real-time brotherhood messaging and nudges.

## Deploy

This is a single `index.html` file. Host it anywhere:

1. **GitHub Pages** — Push to a repo, enable Pages
2. **Netlify** — Drag and drop at app.netlify.com/drop
3. **Local** — Just open the file in any browser

## Setup for GitHub Pages

1. Create a new repo (e.g. `grit-app`)
2. Upload `index.html` to the root
3. Go to Settings → Pages → Source: "Deploy from branch" → Branch: `main` → Save
4. Your app will be live at `https://yourusername.github.io/grit-app`

## Tech

- Pure HTML/CSS/JS — no build step, no framework
- LocalStorage for persistence
- Optional Supabase for multi-user features
- Bible API (bible-api.com) for verse lookup
- Spotify Embed API for worship playback

## License

Personal use. Built for the glory of God.
