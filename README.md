# The Better Wordle 

A polished, feature-rich recreation of the popular word-guessing game— built with vanilla HTML, CSS and JavaScript, with real user accounts and persistent streak tracking powered by Supabase.

Created by **Nirmit Singh (36614812724)** as part of my Summer Internship project at **Graphketing**.

## Features

- **Classic Wordle gameplay** — guess a hidden 5-letter word in 6 tries, with color-coded feedback (🟩 correct, 🟨 present, ⬛ absent)
- **5-minute timer**** per round, with visual warnings as time runs low
- **Light / dark mode** toggle, saved across sessions
- **User accounts** — sign up and log in with a username and password
- **Persistent streak tracking** — current streak, best streak, games played, and win % saved to your profile
- **Profile modal** — view your stats at a glance
- **Result modal** — see your streak update immediately after each game, or a prompt to log in if you're playing as a guest
- **Confetti celebration** on a win 
- **Fully responsive** — desktop, tablet, and mobile layouts
- **Feedback form** for bug reports and reviews

## Tech Stack

- **Frontend:** HTML5, CSS3, vanilla JavaScript (no frameworks)
- **Auth & Database:** [Supabase](https://supabase.com/) (Auth + Postgres)
- **Fonts:** Google Fonts (Fredoka, Poppins, Outfit)

## 📁 Project Structure

```
├── index.html      # Markup and modal structure
├── wordle.css      # All styling, themes, and responsive layout
├── wordle.js       # Game logic, auth, and Supabase integration
└── README.md
```

## Getting Started

1. Clone the repo:
```bash
   git clone https://github.com/nirmitts/the-better-wordle-final.git
```
2. Open `index.html` in a browser, or serve it locally (e.g. with the VS Code "Live Server" extension) — no build step required.

> **Note:** This project connects to a private Supabase backend for authentication and streak tracking. If you fork this repo, you'll need to set up your own Supabase project and replace the credentials in `wordle.js` for accounts and streaks to work.

## How to Play

1. Type a valid 5-letter word and press **Enter**.
2. Tiles reveal how close your guess was:
   - 🟩 **Green** — correct letter, correct position
   - 🟨 **Yellow** — correct letter, wrong position
   - ⬛ **Grey** — letter not in the word
3. You have 6 guesses and 5 minutes. Log in to save your streak across games!

## Developed by **Nirmit Singh**, 36614812724

## License

This project is for educational/portfolio purposes as part of a Summer Internship at Graphketing.
