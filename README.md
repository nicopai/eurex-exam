# FWB Trader Exam PWA

A Progressive Web App for practicing the Frankfurter Wertpapierbörse (FWB) Trader Exam with all 150 official questions.

## Features

- ✅ All 150 official exam questions
- ✅ Study mode with filters by chapter and question type
- ✅ Exam simulation (50 questions, 30 minutes, just like the real exam)
- ✅ Accurate scoring matching real exam rules
- ✅ Bookmarks to save difficult questions
- ✅ Progress tracking (exams taken, best score)
- ✅ Works offline after first load
- ✅ Installable on iOS/Android home screen
- ✅ Data persists locally

## Exam Structure

- **50 questions** from the 150 question catalog
- **30 minutes** duration
- **75% pass mark** (102 out of 136 points)

### Topics Covered

**Part 1: Rules and Regulations**
- 1.1 Exchange Rules I (Exchange bodies)
- 1.2 Exchange Rules II (Technical problems, suspension, market integrity)
- 1.3 Exchange Rules III (Structured Products)
- 1.4 Conditions for Transactions
- 1.5 On-exchange Off-book Trading
- 1.6 Regulated Unofficial Market

**Part 2: Functionality of Trading**
- 2.1 Xetra (Continuous Trading with Auctions)
  - Fundamentals, Trading Process, Orders, Safeguards
  - Designated Sponsor, Price Determination, Off-book Trading
- 2.2 Börse Frankfurt (Continuous Auction with Specialist)
  - Fundamentals, Specialist duties, Price Determination

## How to Host (Free Options)

### Option 1: GitHub Pages (Recommended)

1. Create a GitHub account at github.com
2. Create a new repository named `fwb-exam`
3. Upload all 3 files: `index.html`, `manifest.json`, `sw.js`
4. Go to Settings → Pages → Source → Select "main" branch → Save
5. Your app will be live at: `https://yourusername.github.io/fwb-exam/`

### Option 2: Netlify (Drag & Drop)

1. Go to netlify.com and sign up
2. Drag the entire folder onto the Netlify dashboard
3. Instant deployment

## Installing on Your Phone

### iPhone/iPad:
1. Open the URL in Safari
2. Tap the Share button (square with arrow)
3. Tap "Add to Home Screen"

### Android:
1. Open the URL in Chrome
2. Tap "Add to Home Screen" or "Install App"

## Files

- `index.html` - The main app (self-contained)
- `manifest.json` - PWA configuration
- `sw.js` - Service worker for offline support

---

Good luck with your FWB exam! 🏛
