# Rebase

A daily puzzle game about numeric bases.

**[Play now](https://sean-reid.github.io/rebase/)**

## How it works

Each puzzle gives you 4 digit strings and 4 number bases. Assign one base to each string so the computed values add up to the target sum. You get 3 attempts with Wordle-style feedback after each guess.

The twist: bases include irrational numbers like the golden ratio, sqrt(2), Euler's number, and pi. The same digit string means wildly different things depending on the base.

## Features

- **Daily puzzle** with a new challenge every day, same for everyone
- **Practice mode** with selectable difficulty (easy through expert)
- **Challenge mode** to send puzzles to friends via shareable codes
- **Stats and streaks** tracked locally
- **Shareable results** in the familiar emoji grid format

## Difficulty

Difficulty scales by day of the week:

| Day | Level | Bases |
|-----|-------|-------|
| Mon, Tue | Easy | Integer only (2, 3, 5, 10) |
| Wed, Thu | Medium | Integers + one irrational |
| Fri, Sat | Hard | Multiple irrationals |
| Sunday | Expert | All non-integer bases |

## Tech

Single `index.html` with inline CSS and JS. No frameworks, no build step. Hosted on GitHub Pages.

## License

MIT
