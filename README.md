# PhantomPvP Website

Public McPvP-style site for the **PhantomPvP** network.

## Live test (GitHub Pages)
https://supercoderq123a123g123i12.github.io/PhantomPvP-Website/

## Features
- Top Players podium + list
- Full leaderboard (kit tabs)
- Player stats (W/L, KDR, streaks, skill %)
- Client / Launcher advertising
- Limited-time **Phantom Beta Cloak** claim
- Live data from PhantomDuels plugin API (port 8080)

## How to test
1. Open the Pages URL above.
2. Footer → **Change** → set API to `http://YOUR_SERVER_IP:8080`.
3. Plugin: `api.enabled: true` in config.yml.

## Local
```bash
npx serve .
```
