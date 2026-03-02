# HVAC Control System — Debug Dashboard

A progressive web app (PWA) for HVAC diagnostics and control. Install it directly from your browser — no app store needed.

---

## 🌐 Live App

**[Open in Browser →](https://YOUR-USERNAME.github.io/hvac-debug/)**

> Replace `YOUR-USERNAME` with your GitHub username after deploying.

---

## 📲 Install as an App

### On Android (Chrome)
1. Open the Live App link above in Chrome
2. Tap the **⋮ menu → "Add to Home screen"**
3. Tap **Add** — done!

### On iPhone / iPad (Safari)
1. Open the Live App link in **Safari**
2. Tap the **Share icon (□↑)** at the bottom
3. Scroll down and tap **"Add to Home Screen"**
4. Tap **Add** — done!

### On Desktop (Chrome / Edge)
1. Open the Live App link
2. Look for the **install icon (⊕)** in the address bar on the right
3. Click it and confirm — the app opens in its own window

---

## 🚀 Deploy to GitHub Pages (One-Time Setup)

1. **Create a new GitHub repo** named `hvac-debug` (or any name you like)

2. **Upload these files** to the repo root:
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - `icon-192.png`
   - `icon-512.png`

3. **Enable GitHub Pages:**
   - Go to your repo → **Settings → Pages**
   - Under *Source*, select **Deploy from a branch**
   - Choose **`main`** branch, **`/ (root)`** folder
   - Click **Save**

4. After ~60 seconds, your app will be live at:
   `https://YOUR-USERNAME.github.io/hvac-debug/`

---

## ✨ Features

- Full HVAC diagnostics dashboard
- Works offline after first load (service worker caching)
- Installable as a standalone app on any device
- No server, no backend — runs entirely in the browser
- Settings and alarms saved locally via `localStorage`

---

## 📁 File Structure

```
hvac-debug/
├── index.html      ← Main app (single file)
├── manifest.json   ← PWA install config
├── sw.js           ← Service worker (offline support)
├── icon-192.png    ← App icon (Android / PWA)
├── icon-512.png    ← App icon (large / splash)
└── README.md       ← This file
```
