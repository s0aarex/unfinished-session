# 🎛️ Unfinished Session

![build](https://img.shields.io/badge/build-passing-brightgreen)
![version](https://img.shields.io/badge/version-0.1.0-blue)
![platform](https://img.shields.io/badge/platform-mobile%20%7C%20desktop-lightgrey)
![tech](https://img.shields.io/badge/stack-React%20Native%20%2B%20Tauri-purple)

> A productivity app for music producers focused on ideas, flow state and unfinished projects.

---

## 🧠 What is Unfinished Session?

**Unfinished Session** is a daily productivity system made for music producers.

Most producers:
- start a lot of ideas
- lose inspiration
- overthink small details
- never finish tracks

This app exists to fix **exactly that**.

---

## ✨ Core Features

### 🎼 Daily Starter
Every day, the app generates:
- BPM
- Key
- Vibe

No thinking. Just start.

---

### ⏱️ Guided Sessions
Choose a session mode:
- Sketch (30 min)
- Build (60 min)
- Finish (90 min)

The app guides you step-by-step so you don’t get stuck tweaking forever.

---

### 💡 Idea Capture
- Save ideas as text or audio
- Tag by vibe, BPM or mood
- Never lose ideas again

---

### 🗂️ Unfinished Projects
- Track unfinished songs
- See what’s missing
- Get a suggested **next action**

---

### 🚨 Overthinking Detector
The app detects when you’re stuck too long and tells you to:
> “Commit and move on.”

---

## 📱 Platforms

- 📲 **Mobile**: React Native (Expo)
- 💻 **Desktop**: Tauri + React (Vite)
- 🧠 **Shared Logic**: TypeScript (monorepo)
- 💾 **Offline-first** (SQLite)
- 🤖 **AI-powered assistance**

---

## 🗂️ Project Structure

```txt
unfinished-session/
├─ apps/
│  ├─ mobile/        # React Native (Expo)
│  └─ desktop/       # Tauri + React
├─ packages/
│  └─ shared/        # Core logic, types, rules
├─ docs/
└─ README.md
