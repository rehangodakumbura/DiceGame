# 🎲 Dice Game – Android App (Kotlin + Jetpack Compose)

A fully functional **Dice Game Android application** built using **Kotlin** and **Jetpack Compose**, developed without any third-party libraries.  
---

## 📖 Game Overview
The game is a two-player match: **Human vs Computer**.  
- Both players roll **five dice** per turn.  
- The goal is to reach a **target score** (default: 101, customizable by the player).  
- Players can take up to **optional rerolls** each turn, choosing which dice to keep and which to reroll.  
- The computer uses a **randomized strategy** to decide rerolls.  
- The first player to reach or exceed the target score wins.  
- In the case of a tie, players continue rolling until a winner is determined.

---

## ✨ Features
- 🎲 **Dice Roll Simulation** – Dynamic images for human and computer dice rolls.  
- 🔄 **Optional Rerolls** – Select dice to keep and reroll the rest (up to 2 rerolls).  
- 🤖 **Computer Opponent** – Uses a randomized reroll strategy for gameplay variety.  
- 🏆 **Win Condition & Tie Handling** – Automatically determines the winner with tie-breakers.  
- 🎯 **Custom Target Score** – Allows users to set a different winning score.  
- 📊 **Win Statistics** – Tracks session-based wins for both players.  
- 📱 **Orientation Support** – Seamless handling of device rotation without losing game state.  
- 🧩 **User-Friendly UI** – Built with Jetpack Compose for a modern and responsive experience.

---

## 🛠 Tech Stack
- **Programming Language:** Kotlin  
- **UI Framework:** Jetpack Compose  
- **IDE:** Android Studio (latest version recommended)  
- **Platform:** Android 8.0 (API Level 26) and above

---

## 🚀 How to Run
1. **Clone the repository:**
   ```bash
   git clone https://github.com/rehangodakumbura/DiceGame.git
