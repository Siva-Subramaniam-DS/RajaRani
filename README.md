# Raja Rani Game

A browser version of Raja Rani, the traditional Indian role-card guessing game.

**Play it:** https://siva-subramaniam-ds.github.io/RajaRani/

## How the game works

- The game is played over several rounds.
- Each round, every player is randomly dealt a character card.
- Players score points based on the character they hold.
- The Police player must guess who holds the Thief card.
  - A correct guess wins the Police bonus points.
  - A wrong guess lets the Thief steal points from the Police.

## Characters

| Card | Role |
|---|---|
| Raja (King) | The most powerful card |
| Manthiri (Minister) | The advisor to the King |
| Police | Can catch the Thief for bonus points |
| Thiruden (Thief) | The lowest value card; can steal points from the Police |

The Police role is high risk and high reward, so guess wisely.

## About this repository

This repository holds the built site that GitHub Pages serves (`index.html` and `assets/`). The app was built with React and Vite; the source code is not included here.

To run it locally, serve the folder under the `/RajaRani/` path, since the build expects that base URL.
