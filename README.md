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

## 🛠️ Tech Stack
- **Structure**: Semantic HTML5
- **Styling**: Vanilla CSS3 (Custom Design System with CSS variables, Flexbox & CSS Grid)
- **Logic**: Vanilla JavaScript (ES6+)
- **Graphics**: Inline SVG (Barnaby Mascot & custom iconography)
- **Storage**: Browser `localStorage` API

---

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).
