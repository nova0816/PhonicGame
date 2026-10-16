# Minimal Pair Duel ⚔️ | ESL Phonics Arcade Game

An interactive, responsive HTML5 phonics sound discrimination game designed for ESL / EFL learners, kids, and language teachers.

Distinguish tricky English **Minimal Pairs** (words differing by only a single confusable vowel or consonant sound) in an energetic space-arcade duel against cute monster avatars.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-blue.svg)

---

## 🎮 Key Features

- **7 Progressive Episodes + Custom Teacher Mode:**
  1. **Episode 1:** `/ɪ/` vs `/iː/` (Short I vs Long EE - *Ship* 🚢 vs *Sheep* 🐑)
  2. **Episode 2:** `/æ/` vs `/e/` (Short A vs Short E - *Bat* 🦇 vs *Bet* 🎲)
  3. **Episode 3:** `/l/` vs `/r/` (Liquids & Retroflex - *Light* 💡 vs *Right* ➡️)
  4. **Episode 4:** `/b/` vs `/v/` (Bilabial vs Labiodental - *Berry* 🍓 vs *Very* ⭐)
  5. **Episode 5:** `/p/` vs `/b/` (Voiceless vs Voiced Plosive - *Pig* 🐷 vs *Big* 🐘)
  6. **Episode 6:** `/s/` vs `/θ/` (Hissing vs Dental TH - *Sink* 🚰 vs *Think* 💭)
  7. **Episode 7:** 🔀 **Mixed Phonics Gauntlet** (All 6 contrasts shuffled!)
  - **Custom Teacher List:** Add custom minimal pairs directly via teacher mode.

- **🎧 Pre-Round Practice & Sound Deck:**
  - Before entering each duel, listen to each word card individually.
  - Side-by-side **Compare** button to play both contrasting sounds back-to-back.
  - Phonetic articulation hints (e.g. relaxed jaw vs wide smile).

- **⏱️ Live In-Game Speed Selector:**
  - `🐢 0.25x (Kids)`: 48 seconds per round — relaxed pace for young learners.
  - `🐌 0.5x (Slow)`: 24 seconds per round.
  - `⚡ 1.0x (Normal)`: 12 seconds per round.
  - `🧘 ∞ Practice`: No timer / unlimited thinking time.

- **📱 iPad & Tablet Optimized:**
  - Two-thumb arcade duel posture (side-by-side left/right thumb targets).
  - Direct touch on monster cards with tactile tap feedback.
  - iOS safe-area insets and touch gesture audio unlock.
  - Prevents accidental zooming or text selection.

- **🔊 100% Standalone (Zero External Audio Dependencies):**
  - Synthesized retro arcade SFX using Web Audio API (`AudioContext`).
  - Native Web Speech API (`SpeechSynthesis`) with selectable voices and adjustable voice rates.

---

## 🚀 How to Run

No build step or server required!

1. Clone or download this repository:
   ```bash
   git clone https://github.com/nova0816/PhonicGame.git
   ```
2. Open `index.html` in any modern web browser (Chrome, Edge, Safari, Firefox) on Desktop, iPad, or mobile device.

---

## 🕹️ Controls

| Action | iPad / Touch | Keyboard |
|---|---|---|
| Select Left Target | Tap Left Monster Card or "Launch Left" | `Left Arrow [←]`, `[A]`, or `[1]` |
| Select Right Target | Tap Right Monster Card or "Launch Right" | `Right Arrow [→]`, `[D]`, or `[2]` |
| Replay Target Word | Tap Speaker button `🔊` | `[Spacebar]` |
| Close Overlays / Menus | Tap `✕` or Close button | `[Escape]` |

---

## 📄 License
MIT License. Feel free to use and adapt for educational classrooms and learning games!
