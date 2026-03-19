# 🇩🇰 Dansk Daglig — GitHub Pages Hosting Guide

## What you need
- A free GitHub account (sign up at github.com)
- The `Dansk-Daglig-v2.html` file (rename it to `index.html`)

## Step-by-step setup (5 minutes)

### 1. Create a GitHub account (skip if you have one)
- Go to **github.com** → Sign up
- Verify your email

### 2. Create a new repository
- Click the **+** button (top right) → **New repository**
- Name it: `dansk-daglig`
- Set it to **Public**
- Check **"Add a README file"**
- Click **Create repository**

### 3. Upload your app
- In your new repository, click **Add file** → **Upload files**
- **Important:** Rename `Dansk-Daglig-v2.html` to `index.html` before uploading
- Drag and drop `index.html` into the upload area
- Click **Commit changes**

### 4. Enable GitHub Pages
- Go to your repository's **Settings** tab (gear icon)
- In the left sidebar, click **Pages**
- Under "Source", select **Deploy from a branch**
- Under "Branch", select **main** and **/ (root)**
- Click **Save**
- Wait 1-2 minutes for deployment

### 5. Access your app
- Your app will be live at: `https://YOUR_USERNAME.github.io/dansk-daglig/`
- Bookmark this URL or add it to your home screen

## Add to Home Screen (make it feel like a real app)

### Android (Chrome):
1. Open your GitHub Pages URL in Chrome
2. Tap the **three dots menu** (⋮) → **Add to Home screen**
3. Name it "Dansk Daglig" → Tap **Add**
4. The app icon appears on your home screen!

### iPhone (Safari):
1. Open your GitHub Pages URL in Safari
2. Tap the **Share button** (□↑) → **Add to Home Screen**
3. Name it "Dansk Daglig" → Tap **Add**

## What works after hosting

| Feature | File:// (before) | GitHub Pages (after) |
|---------|:-:|:-:|
| Conversations | ✅ | ✅ |
| Flashcards | ✅ | ✅ |
| Material upload | ✅ | ✅ |
| Gemini TTS (voice output) | ✅ | ✅ |
| Voice input (speech-to-text) | ❌ | ✅ |
| Data persists between sessions | ❌ | ✅ |
| Add to home screen | ❌ | ✅ |

## Updating the app

When you get a new version:
1. Go to your repository on github.com
2. Click on `index.html`
3. Click the **pencil icon** (Edit) or delete and re-upload
4. Commit the changes
5. Wait 1-2 minutes — your live app updates automatically

## Your data is safe

- Your API key, flashcard progress, and materials are stored in your browser's localStorage
- This data NEVER goes to GitHub — it stays on your device
- Each person who visits your URL has their own empty app

## Troubleshooting

**App doesn't load?**
- Make sure the file is named exactly `index.html` (lowercase)
- Check that GitHub Pages is enabled in Settings → Pages
- Wait 2-3 minutes after enabling — first deploy takes a moment

**Voice still doesn't work?**
- Make sure you're accessing via `https://` (not `http://`)
- Grant microphone permission when Chrome asks
- Try refreshing the page after granting permission

**Lost your data?**
- Clearing browser data/cache will erase localStorage
- Don't use incognito mode — localStorage doesn't persist there
