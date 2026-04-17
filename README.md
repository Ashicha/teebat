# ShuttleCourt 🏸
**2v2 Badminton Matchmaking & Tournament App**

A mobile-first web app to manage badminton matches and tournaments.

## Features
- Add/manage players with skill levels
- 2v2 matchmaking with team shuffling
- Live score tracking per match
- Single-elimination tournament bracket
- Works on any phone browser (PWA-ready)
- Persists data in localStorage

---

## Run Locally

```bash
npm install
npm start
# Open http://localhost:3000 on your phone (same WiFi)
```

To access from your phone on the same WiFi, find your computer's local IP:
- Mac: `ipconfig getifaddr en0`
- Windows: `ipconfig` → look for IPv4
Then open `http://YOUR_IP:3000` on your phone.

---

## Deploy for Free (recommended)

### Option 1: Railway (easiest, free tier)
1. Push this folder to GitHub
2. Go to https://railway.app → New Project → Deploy from GitHub
3. Select your repo → it auto-detects Node.js
4. Done! Get a public URL to share

### Option 2: Render (free tier, sleeps after inactivity)
1. Push to GitHub
2. Go to https://render.com → New Web Service
3. Connect your repo
4. Build command: `npm install`
5. Start command: `npm start`
6. Done!

### Option 3: Fly.io (always-on free tier)
```bash
npm install -g flyctl
fly auth login
fly launch
fly deploy
```

---

## Share with your friends
Once deployed, just share the URL — works on any phone browser, no app install needed.
