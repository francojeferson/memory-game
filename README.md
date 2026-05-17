# Memory Game

A classic memory card matching game built with React 19. Pick a category, choose how many cards to play with, and match all the pairs.

## Features

- Category selection with themed emoji sets
- Configurable grid size
- Card flip animation with visual feedback
- Match detection and score tracking (moves + timer)
- Responsive grid layout (mobile to desktop)
- Dark theme

## Status

This project is in early development. Core game logic (shuffling, match checking, score tracking, game-over detection) is not yet implemented. The component scaffolding, CSS animations, and form layout are in place.

## Setup

```bash
npm install
npm start
```

Opens [http://localhost:3000](http://localhost:3000) in development mode.

## Scripts

| Command | Description |
|---------|-------------|
| `npm start` | Start dev server on port 3000 |
| `npm test` | Run tests in watch mode |
| `npm run build` | Build for production to `build/` |
| `npm run eject` | Eject CRA config (one-way) |

## Tests

```bash
npm test
```

Uses React Testing Library. Current tests cover: title render, form visibility on load, and card grid appearance after game start.

## Tech Stack

- React 19
- Create React App 5
- React Testing Library
- Inter (Google Fonts)

## Author

[Franco Jeferson](https://github.com/francojeferson)

## License

MIT
