# AgriTech 2026 | Hackathon Problem Statement Spinner 🌾💻📊

A single-page, self-contained interactive web application built for cross-discipline hackathons with 2-member teams across **Computer Science (CS)**, **Data Science (DS)**, and **Agriculture (Agri)** backgrounds.

## 🚀 Key Features

- **Automated Category Computation**: Instantly computes team categories (`CS+CS`, `CS+DS`, `Agri+CS`, `DS+DS`, `Agri+DS`, `Agri+Agri`) regardless of member selection order.
- **Interactive HTML5 Canvas Wheel**: Features visual slice rendering, smooth deceleration physics, tick sound effects & victory fanfare using Web Audio API, and confetti particle FX upon lock-in.
- **Immediate Atomic Problem Assignment & Locking**: Once a team spins, their problem assignment is stamped as **LOCKED & ASSIGNED**, instantly removed from the open pool, and persisted across sessions.
- **Multi-Tab / Multi-Window Sync**: Native cross-tab real-time state synchronization via `localStorage` and `BroadcastChannel`.
- **Pre-Loaded 24 Realistic Problem Statements**: 4 curated, domain-specific, realistic problem statements per category blending agriculture, software engineering, and data science.
- **Organizer / Admin Desk**: Tab for organizers to monitor live assignments, add custom problems, search/filter problem statuses, export assignment CSV reports, and reset data.

## 🛠️ Usage

1. Open `index.html` directly in any modern web browser or host it via GitHub Pages.
2. Enter your Team Name and select Member 1 & Member 2 backgrounds.
3. Click **SPIN PROBLEM WHEEL** to lock in your hackathon problem!

## 📜 License

MIT License
