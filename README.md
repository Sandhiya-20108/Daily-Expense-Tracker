# ExpenseFlow 🐾 Cute Gamified Daily Expense Tracker

A delightful, privacy-first personal finance tracker featuring **Barnaby the Bear**, interactive gamification (XP levels, quests, badges, streaks), savings goals, and a curated **Pastel Purple + Warm Cream** aesthetic.

Built with clean **Vanilla HTML5, CSS3, and JavaScript** — entirely self-contained with zero runtime dependencies.

---

## ✨ Key Features

### 🌸 Pastel Purple + Warm Cream Aesthetic
- Curated color harmony using warm cream (`#FFF8EE`), cream-white cards (`#FFFCF6`), and pastel lavender/purple accents (`#896EB8`, `#55416F`).
- Soft sage green (`#2D7A4F`) for income and warm terracotta (`#C75656`) for expenses.
- Deep royal purple gradient featured card displaying live current balance.
- Smooth transitions, micro-interactions, and responsive layouts for desktop, tablet, and mobile.

### 🐻 Barnaby Bear & Gamification Hub
- **Barnaby the Mascot**: Handcrafted vector SVG companion with caramel fur, peach ears, cream snout, and pink blush cheeks.
- **Dynamic Speech Bubble**: Barnaby offers contextual financial tips, cheerleading, and celebration messages.
- **Daily Check-In**: Earn daily streak bonuses and check-in rewards (`+5 XP`).
- **XP & Levels System**:
  - 🌱 **Level 1: Money Seed** (0 - 24 XP)
  - 🐻 **Level 2: Budget Explorer** (25 - 59 XP)
  - ⭐ **Level 3: Saving Star** (60 - 99 XP)
  - 👑 **Level 4: Money Master** (100+ XP)
- **Daily Quests & Streaks**: Consecutive tracking tracking streaks across calendar days.
- **Milestone Badges**: 6 unique achievements (First Step, Daily Check-In, 3-Day Tracker, Budget Buddy, Goal Getter, Consistency Star) with pop-up celebration toasts.

### 💰 Comprehensive Financial Tracking
- **Formula-Accurate Balances**: `Starting Balance + Total Income - Total Expenses = Current Balance`.
- **Daily Spending Budget**: Real-time spending progress bar with safe spending limits.
- **Today's Money Recap**: Quick overview of today's income, expenses, net change, and top spending category.
- **Categorized Logging**: Quick logging for Food & Dining, Shopping, Groceries, Entertainment, Bills & Utilities, Transport, Salary, Freelance, and more.
- **Savings Goals**: Target tracking for personal milestones (e.g. Desk Setup, Emergency Fund) with interactive progress meters.
- **Transaction History**: Filterable, searchable transaction feed with CSV export support.

### 🔒 Privacy-First Client Architecture
- **100% Client-Side**: All data is saved exclusively inside your browser's `localStorage`.
- **Multi-Account Support**: Switch between multiple user profiles with scoped data isolation.
- **Zero External Tracking**: No telemetry, analytics, or external server calls.

---

## 🚀 Getting Started

No installation or build steps required!

### Option 1: Direct File Open
Simply double-click [`index.html`](index.html) or open it in any modern web browser (Google Chrome, Microsoft Edge, Firefox, Safari).

### Option 2: Run via Local HTTP Server
Using Python:
```bash
python -m http.server 3000
```
Then visit [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📱 Mobile & Progressive Web App (PWA)

ExpenseFlow is a fully installable Progressive Web App (PWA) optimized for mobile touchscreens:

### 🤖 On Android (Google Chrome):
1. Open the website URL in Google Chrome.
2. Tap the **"Add to Home Screen"** prompt banner or tap the Chrome three dots menu (**⋮**).
3. Select **"Install app"** or **"Add to Home screen"**.
4. The cute ExpenseFlow icon will appear directly on your home screen and open in standalone fullscreen mode without browser URL bars!

### 🍎 On iPhone / iPad (Safari):
1. Open the website URL in Safari.
2. Tap the **Share** button (square icon with an arrow pointing upward 📤).
3. Scroll down and select **"Add to Home Screen"** (➕).
4. Tap **Add** in the top right corner. ExpenseFlow is now accessible right alongside your native iOS apps!

---

## ⚠️ Important Note About LocalStorage & Multi-Device Sync

> [!IMPORTANT]
> **Data stays private on your local device:**  
> ExpenseFlow uses the browser's built-in `localStorage` API. Because all data is stored exclusively on the device and browser you are currently using, records created on your computer **will not automatically sync** to your mobile phone. 
> To use the app on your phone, you can create a profile on your phone and track expenses on the go.

---

## ☁️ Deploy to Vercel (1-Click)

To make your ExpenseFlow tracker accessible from your phone anywhere without keeping your computer on:
1. Go to [vercel.com](https://vercel.com) and log in with your GitHub account.
2. Click **"Add New Project"** → select **"Daily-Expense-Tracker"** from your repositories.
3. Keep the default settings (Framework Preset: *Other*, Root Directory: `./`).
4. Click **"Deploy"**.
5. Vercel will build and assign you a free HTTPS live URL (e.g. `https://daily-expense-tracker-sandhiya.vercel.app`) that you can open on your phone and install to your Home Screen!

---

## 🛠️ Tech Stack
- **Structure**: Semantic HTML5
- **Styling**: Vanilla CSS3 (Custom Design System with CSS variables, Flexbox & CSS Grid)
- **Logic**: Vanilla JavaScript (ES6+)
- **Graphics**: Inline SVG (Barnaby Mascot & custom iconography)
- **Offline / PWA**: Web App Manifest (`manifest.json`) & Service Worker (`sw.js`)
- **Storage**: Browser `localStorage` API

---

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).
