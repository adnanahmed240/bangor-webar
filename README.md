# Bangor WebAR – Environmental Data Overlay

**Module:** ICE-4711-0 XReality 2025/26 — Assignment III  
**Scenario:** 1 – Handheld Augmented Reality  
**Stack:** A-Frame v1.7 + AR.js + WebXR Device API

## Live Demo
https://adnanahmed240.github.io/bangor-webar/

## What it does
A browser-based WebAR application that superimposes simulated environmental data (AQI, temperature, noise, humidity, PM2.5) over real-world Bangor landmarks. Two modes:

- **Marker Mode** – point camera at the Hiro marker (print `marker/hiro.png`)
- **Location Mode** – tap a Bangor landmark to view its data panel

All data values are **simulated** for demonstration purposes.

## Deployment (GitHub Pages)

1. Create a new GitHub repo (e.g. `bangor-webar`)
2. Upload all files from this folder to the repo root
3. Go to **Settings → Pages → Source: main branch / root**
4. GitHub will provide a URL — paste it into your paper

## Files
```
index.html      ← main application
data.json       ← environmental data for 3 Bangor landmarks
marker/         ← Hiro marker image (print for marker mode)
README.md
```

## Printing the Marker
Print `marker/hiro.png` at approximately A5 size on white paper. Hold it flat under adequate lighting. Point Chrome on Android at it.

## Browser Support
- ✅ Chrome on Android (full WebXR AR support)
- ⚠ Safari on iOS (WebXR AR not supported — app shows compatibility notice)
- ✅ Desktop Chrome (location mode works; marker mode requires camera)

## Notes
- Camera and location permissions must be granted
- Host must be served over HTTPS (GitHub Pages satisfies this)
