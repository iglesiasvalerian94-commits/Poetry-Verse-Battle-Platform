# Poetry Verse Battle Platform

A website where users vote on french poetry verse duels. Each battle opposes two verses head-to-head — Elo scores are updated after each result. The leaderboard ranks all verses by their current Elo score.

## 🚧 Status

Work in progress — early stage.

## 🛠️ Tech Stack

- HTML / CSS / JavaScript
- PHP
- MySQL (phpMyAdmin / XAMPP)

## 📁 Structure

```
/
├── index.html
├── style.scss
└── ...
```

## ⚔️ How it works

1. **Sign up** — Create an account to participate
2. **Vote** — Each round presents two french poetry verses head-to-head. Pick the one you think is best
3. **Elo system** — After each vote, the winning verse gains Elo points and the losing verse drops. The bigger the upset, the bigger the Elo swing
4. **Leaderboard** — All verses are ranked by their current Elo score, reflecting the community's taste in real time

## 🚀 Run locally

1. Clone the repo
2. Move the project folder into your XAMPP `htdocs` directory
3. Start Apache & MySQL in XAMPP
4. Open `http://localhost/Poetry-Verse-Battle-Platform`
