# AIQ — How deep does your AI knowledge go?

> **The machines are learning. Are you?**

AIQ is a free, daily AI quiz and trivia game. Test your knowledge across AI history, concepts, tools, numbers, and logo identification. New questions every day. No account needed.

🌐 **Live:** [https://devanshiagarwal1034.github.io/aiq-quiz/](https://devanshiagarwal1034.github.io/aiq-quiz/)

---

## Features

- **6 categories** — AI History, AI Concepts, AI Tools, Wild Numbers, Spot the Logo, and Misc Mix
- **Daily questions** — fresh set of 10 questions every day using a date-based seed, same for all players
- **Shared leaderboard** — live global leaderboard powered by JSONBin
- **Streak tracking** — play daily to build your streak
- **No signup, no tracking** — just enter a nickname and play
- **Works offline** — single HTML file, no dependencies to install

---

## Categories

| Category | Description |
|---|---|
| 📜 AI History | Milestones, pioneers, and key moments in AI |
| 🧠 AI Concepts | LLMs, transformers, GANs, RLHF and more |
| 🔧 AI Tools | ChatGPT, Claude, Midjourney and beyond |
| 📊 Wild Numbers | Parameters, funding, benchmarks, stats |
| 🎨 Spot the Logo | Identify AI brands from their visual marks |
| 🎲 Misc Mix | Random questions from all categories |


## Leaderboard Setup

The shared leaderboard uses [JSONBin.io](https://jsonbin.io) — a free JSON storage service.

The leaderboard is already configured in this build. All players who visit the live site share the same leaderboard automatically.

---

## Tech Stack

- Pure HTML, CSS, JavaScript — no frameworks, no build tools
- Inline SVG logos — no external image dependencies
- JSONBin API — for shared leaderboard persistence
- localStorage — for streak and local score tracking
- GitHub Pages — for free static hosting

---

## Project Structure

```
aiq-quiz/
└── index.html   # Entire app — all code, styles, questions, and logos in one file
```

---

## Contributing

Found a wrong answer or want to suggest new questions? Open an issue or submit a pull request. All contributions welcome!


---

*Built with ❤️ for AI enthusiasts everywhere.*
