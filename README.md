# Re. — Made to Re-make minds.

A personalised self-reflection web app. No backend. No database. No accounts. Pure HTML/CSS/JS.

## Deploy in 60 seconds

### Option A — Vercel
1. Go to vercel.com → sign up free
2. Install Vercel CLI: npm i -g vercel
3. Run: vercel --prod
4. Done.

### Option B — GitHub Pages (free forever)
1. Create a GitHub repo
2. Push this folder to the repo
3. Go to Settings → Pages → Deploy from main branch
4. Live at: yourusername.github.io/re-app

## PWA (installable on phones)
This app is a Progressive Web App. Users can install it to their home screen from any browser:
- iPhone: Safari → Share → "Add to Home Screen"
- Android: Chrome → menu → "Add to Home Screen"
- It works offline once installed.

## iOS App Store (no Mac needed)
Use PWABuilder (pwabuilder.com):
1. Enter your live URL
2. Download the iOS package
3. Use a Mac service (MacinCloud ~$1/hr) to submit via Xcode
4. Apple Developer account required ($99/yr)

## Files
- index.html — the entire app
- manifest.json — PWA config
- sw.js — service worker (offline support)
- icon-192.png / icon-512.png — app icons
- vercel.json — Vercel config
