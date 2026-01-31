# 🎛️ Unfinished Session

> A productivity app for music producers focused on ideas, flow state and unfinished projects.

**Unfinished Session** is built for producers who start a lot of ideas, overthink details, and struggle to finish tracks.  
The goal is simple: **create every day and finish what you start**.

---

## 🧠 Why Unfinished Session?

Most producers:
- open a DAW
- start something cool
- tweak forever
- abandon the project

Unfinished Session turns music creation into **guided sessions**, helping you stay in flow and avoid overthinking.

Built by a producer, for producers.

---

## ✨ Core Features

### 🎼 Daily Starter
Every day the app generates:
- BPM
- Key
- Vibe

No decision fatigue. Just start creating.

---

### ⏱️ Guided Sessions
Choose your focus mode:
- **Sketch** – 30 minutes
- **Build** – 60 minutes
- **Finish** – 90 minutes

Each session keeps you focused and time-boxed.

---

### 🚦 Anti-Overthinking System
- Clear session goals
- Time limits
- (Planned) progress tracking and nudges

The app helps you **commit and move on**.

---

### 🗂️ Unfinished Projects (Planned)
- Track ideas and unfinished tracks
- See what’s missing
- Get a suggested next action

---

## 📱 Platforms

- 📲 **Mobile**: React Native + Expo
- 💻 **Desktop (Planned)**: Tauri + React
- 🤖 **AI (Planned)**: smart suggestions & organization

---

## 🧱 Current Tech Stack

- React Native
- Expo Router
- TypeScript
- Expo Go (development)
- Local logic (offline-first mindset)

---

## 🗂️ Project Structure

```txt
app/
├─ (tabs)/index.tsx     # Home (Daily Starter + modes)
├─ session.tsx          # Active session (timer)
├─ utils/
│  └─ dailyStarter.ts   # BPM / Key / Vibe logic
