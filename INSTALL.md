# 🏍️ Navi Routes — Install on Your Phone

## Option 1: Easiest — GitHub Pages (Free, 5 min setup)

This hosts your app online so you can install it like a real app on Android.

### Step 1: Create a free GitHub account
Go to https://github.com and sign up (free).

### Step 2: Create a new repository
- Click the "+" button → "New repository"
- Name it: `navi-routes`
- Make it **Public**
- Click "Create repository"

### Step 3: Upload the 3 files
- Click "uploading an existing file"
- Drag and drop: `index.html`, `manifest.json`, `sw.js`
- Click "Commit changes"

### Step 4: Turn on GitHub Pages
- Go to Settings → Pages
- Under "Source" select: **Deploy from a branch**
- Branch: **main** / folder: **/ (root)**
- Click Save

Your app will be live in ~1 minute at:
`https://YOUR-USERNAME.github.io/navi-routes`

### Step 5: Install on Android
1. Open Chrome on your Android phone
2. Visit your GitHub Pages URL above
3. Tap the **⋮ menu** (3 dots, top right)
4. Tap **"Add to Home screen"**
5. Tap **"Install"**

✅ Done! It now appears in your app drawer with a full-screen experience.

---

## Option 2: Get a Real APK (via Median.co)

If you want an actual `.apk` file:

1. First complete Option 1 to get your app URL
2. Go to https://median.co
3. Click "Create App" — enter your GitHub Pages URL
4. It builds a native Android APK for free (basic tier)
5. Download the APK, transfer to phone, install

(You may need to enable "Install from unknown sources" in Android settings)

---

## Option 3: Quick Local Test (same WiFi)

If you just want to test on your phone right now:
1. Install Python on your computer
2. Open terminal/command prompt in the navi-app folder
3. Run: `python -m http.server 8080`
4. On your phone, open Chrome and go to: `http://YOUR-COMPUTER-IP:8080`
5. Add to Home Screen from there

---

## Features in the app
- 📍 "Use My Location" button sets your start point automatically
- ⚙️ Settings gear opens speed preference & avoidance options
- Speed slider: 25 / 35 / 45 / 55+ mph preference
- Always avoids highways/freeways
- Toggle: avoid toll roads, avoid ferries
- Shows distance (miles) + estimated ride time
- Dark map theme (easy on eyes while riding)

**Keep your index.html private** — your API key is stored inside it.
