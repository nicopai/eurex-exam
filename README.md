# Eurex Trader Exam PWA

A Progressive Web App for practicing the Eurex Trader Exam with all 105 official questions.

## Features

- ✅ All 105 official exam questions
- ✅ Study mode with filters by chapter and question type
- ✅ Exam simulation (35 questions, 20 minutes, just like the real exam)
- ✅ Accurate scoring matching real exam rules
- ✅ Bookmarks to save difficult questions
- ✅ Progress tracking (exams taken, best score)
- ✅ Works offline after first load
- ✅ Installable on iOS/Android home screen
- ✅ Data persists locally

## How to Host (Free Options)

### Option 1: GitHub Pages (Recommended)

1. Create a GitHub account at github.com if you don't have one
2. Click "New Repository" and name it `eurex-exam` (or anything you like)
3. Upload all 3 files: `index.html`, `manifest.json`, `sw.js`
4. Go to Settings → Pages → Source → Select "main" branch → Save
5. Your app will be live at: `https://yourusername.github.io/eurex-exam/`

### Option 2: Netlify (Drag & Drop)

1. Go to netlify.com and sign up
2. Drag the entire `eurex-pwa` folder onto the Netlify dashboard
3. Your app is instantly live at a netlify.app URL

### Option 3: Vercel

1. Go to vercel.com and sign up with GitHub
2. Import your repo or drag the folder
3. Instant deployment

## Installing on Your Phone

### iPhone/iPad:
1. Open the URL in Safari
2. Tap the Share button (square with arrow)
3. Scroll down and tap "Add to Home Screen"
4. Name it "Eurex Exam" and tap Add

### Android:
1. Open the URL in Chrome
2. You'll see an "Install" banner, or tap the 3-dot menu
3. Tap "Add to Home Screen" or "Install App"

## Files

- `index.html` - The main app (self-contained)
- `manifest.json` - PWA configuration (icon, name, etc.)
- `sw.js` - Service worker for offline support

## Technical Notes

- All data stored locally in browser's localStorage
- No server required - fully static files
- Works offline after first visit
- Mobile-optimized UI with safe area support

## Valid Until

These questions are valid for Eurex exams from 03.03.2025 to 20.03.2026.

---

Good luck with your exam! 📈
