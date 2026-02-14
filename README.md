# Pizza Menu

A small React app that showcases a pizza menu with a clean, retro-inspired layout. It renders menu items from local data, highlights sold-out items, and shows store hours with a simple open/closed message.

## Live Demo

GitHub Pages: https://ahmed-adel-morsi.github.io/Pizza-Menu/

## Features

- Menu grid generated from local data in `src/index.js`.
- Sold-out styling (grayscale + muted text) for unavailable pizzas.
- Dynamic footer message based on the current time.
- Simple, responsive layout using CSS Grid and Flexbox.

## Tech Stack

- React (Create React App)
- CSS (single file in `src/index.css`)
- `gh-pages` for deployment

## Getting Started

### 1) Install dependencies

```bash
npm install
```

### 2) Run the app locally

```bash
npm start
```

Open http://localhost:3000 in your browser.

## Available Scripts

- `npm start` - Runs the app in development mode.
- `npm test` - Launches the test runner in watch mode.
- `npm run build` - Builds the app for production.
- `npm run deploy` - Builds and publishes to GitHub Pages.

## Deployment Notes

This project uses `gh-pages` and the `homepage` field in `package.json` to build for the correct base path.

If you change the repo name or GitHub username, update:

- `homepage` in `package.json`
- The `origin` remote (or the `deploy` script)

## Project Structure

```
public/
  index.html
  pizzas/
src/
  index.css
  index.js
```

## Credits

Built while learning React from Jonas Schmedtmann's course.
